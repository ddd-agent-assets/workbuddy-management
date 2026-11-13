# 2 配套资产：公司 GitHub 与登记台账（内部链接汇总）

**结论**：WorkBuddy 管理相关的两个公司级资产入口汇总在这篇——**公司 GitHub 组织**（存配置/脚本/提示词）和**登记台账**（企微在线表格）。都是内部链接，需公司账号打开。

## 一、公司 GitHub：配置与脚本统一存这里，仓库必须私有

- **组织地址**：<https://github.com/ddd-agent-assets>
- **管理员**：AIC Rosetta、客服主管 Yomi
- **三条硬规矩**：GitHub 账号**必须用公司邮箱注册**（禁止个人邮箱）；仓库**必须 Private**（禁止公开）；**凭证不入库**（Bot ID/Secret、连接器 token、mcp.json 密钥只填配置界面）
- 操作细则见 [[05-公司管理流程/04-配置存公司GitHub-必须私有仓库|管理流程：配置存GitHub]]

## 二、知识库（SOP 文档本身）

- **本库（WorkBuddy 管理流程）**：<https://github.com/ddd-agent-assets/workbuddy-management>（建仓后以此为准）
- **前库（企微智能机器人 SOP）**：<https://github.com/ddd-agent-assets/bot-OA-SOP>——自建 API 机器人场景仍以前库为全量参考，两库红线一致、流程互认

## 三、登记台账：暂行用企微在线表格，目前只有客服部的表

- **暂行方案**：WorkBuddy 场景与机器人的登记与维护记录，统一用企业微信在线表格做台账；
- **现有表格（客服部）**：<https://doc.weixin.qq.com/sheet/e3_ATQAYwb8ABcCNRzkGIa8zRp09QEV1?scode=AGwA7wemAAg4gcPPlxAesA0gZZAOs&tab=BB08J2>
- ⚠️ 注意：这张表**目前只是客服部的台账，还不是企业通用的**，且字段是前库的 7 字段版。其他部门先参照[[05-公司管理流程/03-登记台账-在线表格|管理流程：登记台账]]的 **12 字段**（新增使用形态、连接器清单、大圆关联、定时任务、账号类型）自建或等待企业通用版，建好后更新这篇。

## 四、官方入口速查（外部链接）

| 入口 | 地址 |
| :--- | :--- |
| 企微 × WorkBuddy 官方页 | <https://work.weixin.qq.com/nl/index/workbuddy> |
| 帮助中心（领用/管理端/计费） | doc_id 21743-21747，见[[06-提议与附录/03-附录-证据与信源|附录：证据与信源]] |
| WorkBuddy 官方文档 | <https://www.workbuddy.ai/docs> |
| wecom-cli 官方仓库 | <https://github.com/WecomTeam/wecom-cli> |
