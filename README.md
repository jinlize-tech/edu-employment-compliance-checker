# edu-employment-compliance-checker

- 产品名称：`edu-employment-compliance-checker`
- 产品编号：`JLZ-EDU-SK-061`
- 产品类型：Skill
- 所属业务板块：06 人力组织中心
- 作者/维护方：广州金励泽科技服务有限公司
- 研发版本：1.1.0
- 当前状态：**EDUCATION_1.1.0_PRE_RELEASE_ACCEPTED / MODEL_RUNTIME_NOT_VERIFIED**
- 产品规格书：[PRODUCT_SPEC.md](PRODUCT_SPEC.md)
- 使用说明：[USAGE.md](USAGE.md)
- 安装包：[`dist/edu-employment-compliance-checker-v1.1.0.zip`](dist/edu-employment-compliance-checker-v1.1.0.zip)

## 产品功能

劳动用工合规风险检查。

- 主要输入：用工地区、岗位、合同类型、工时安排、薪酬结构和现有制度摘要
- 主要输出：风险检查表、待核实法规项、证据需求、整改优先级和升级建议

## 本地验证

- 测试案例：[tests/TEST_CASES.md](tests/TEST_CASES.md)
- 结构测试：[tests/validate_package.ps1](tests/validate_package.ps1)
- 测试结果：[test-results/v1.1.0.json](test-results/v1.1.0.json)
- 用户体验：[USER_EXPERIENCE.md](USER_EXPERIENCE.md)
- 专业工作手册：[references/PROFESSIONAL_PLAYBOOK.md](references/PROFESSIONAL_PLAYBOOK.md)
- 升级记录：[EDUCATION_1.1.0_UPGRADE_RECORD.md](EDUCATION_1.1.0_UPGRADE_RECORD.md)

本地通过证明文件结构、产品契约、分层测试、确定性脚本和安装包完整性通过；生成式模型行为仍为 MODEL_RUNTIME_NOT_VERIFIED，不代表 WorkBuddy 解析、安装、调用或审核通过。

## 依赖与数据

- 第三方运行依赖：无。
- 默认外部API：无。
- 不要求用户提供API Key。
- 仅处理用户主动提供或明确授权的数据。

## 开源许可证

License: Apache-2.0.

本仓库为免费开放的开源项目。任何人均可依照 Apache License 2.0 使用、修改和分发本项目内容。完整法律条款见 [LICENSE](LICENSE)。
