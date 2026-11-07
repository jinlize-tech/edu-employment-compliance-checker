# G5/G9 产品修改记录

- 产品编号：$(@{number=75; product_id=JLZ-EDU-SK-061; chinese_name=劳动用工合规检查; english_name=Employment Compliance Checker; repository_name=edu-employment-compliance-checker; repository_url=https://github.com/jinlize-tech/edu-employment-compliance-checker; product_type=Skill; category_code=06; category=06 人力组织中心; description=劳动用工合规风险检查。; target_users=System.Object[]; core_input=用工地区、岗位、合同类型、工时安排、薪酬结构和现有制度摘要; main_output=风险检查表、待核实法规项、证据需求、整改优先级和升级建议; product_risk=把非法律专业输出当正式法律意见或遗漏地区差异; dedup_label=无明显重复; dedup_note=与财税OS无关，不提供税务判断；与通用合规检查相比限定教培用工场景，仍要求人工和法律专业复核。; development_status=Planned / 待研发; license=Apache-2.0; spec_version=1.0.0; workbuddy_status=PLANNED_FOR_WORKBUDDY}.product_id)
- 产品名称：劳动用工合规检查
- 基线：EDUCATION_BASELINE_V1.0.0
- 基线提交：$BaselineCommit
- 原版本：1.0.0
- 新版本：1.0.1

## 本次修改

1. 强化产品专属执行流程、输入核对和输出验收规则。
2. 新增 scripts/validate_input.js，实际检查必填字段、冲突、未确认数据和敏感信息。
3. 新增正常、缺失、冲突、敏感信息和非法JSON场景输入。
4. 测试升级为 T1–T7 分层并保存逐项检查结果。
5. 安装包加入 Apache-2.0 LICENSE 和 THIRD_PARTY_NOTICES.md。
6. 安装包升级为 1.0.1，加入许可证、第三方声明和输入校验脚本，保留 1.0.0 ZIP。
7. 按本产品冻结规格补充专属处理规则、输入到成果的核对矩阵和去重边界。

## 产品专属增强

- 核心任务：劳动用工合规风险检查。
- 主要风险：把非法律专业输出当正式法律意见或遗漏地区差异
- 去重边界：与财税OS无关，不提供税务判断；与通用合规检查相比限定教培用工场景，仍要求人工和法律专业复核。

- 从岗位任务、汇报关系、任职资格、协作接口和绩效证据出发，不针对个人画像。
- 区分必要条件与可培养条件，避免歧视性、无限扩张或不相关限制。
- 涉及劳动关系、纪律、薪酬和合规结论时要求专业人员复核。
- 招聘、培训、绩效和入职材料应保留责任人、时间与确认节点。

## 运行边界

- 本地模型行为：NOT_RUNTIME_VERIFIED
- WorkBuddy平台验证：WORKBUDDY_VALIDATION_NOT_IN_SCOPE
- 本轮不执行上传、安装、审核或正式发布。
