# Steedos 使用指南

### 审批王

审批王是全新的企业级在线审批系统，可以快速的将公司的各类审批业务转换为可严格执行的电子流程。审批王可以提供审批的业务包括：出差申请、差旅报销、请假销假、物品采购、付款申请、固定资产报废、会议室预约、退库管理、客服投诉、工作报告等。

审批王的产品功能包括：
- 规范业务范围。审批王帮助您将各项规章制度转化为可严格执行的电子流程。避免工作人员办事随心所欲；
- 减少出错机会。每月月底审批王通过程序自动计算汇总生成报表，避免人工计算、誉抄等环节中的错误；
- 提升工作效率。审批王可以像微信一样即时发送审批通知，无论审批领导处在何地均可通过手机移动办公，大幅度提升业务流程运作效率；
- 记录随时可查。审批王永久保存您的申请单，您可以像百度一样随时查阅搜索已审批的记录，资料不再遗失；
- 降低沟通成本。有了审批王，员工不再到处找领导各种签字，可以大幅度节约纸张、电话、沟通、查询等各种成本；
- 随时随地访问。有了审批王，打开手机就可以处理和查询业务流程，全世界都是您的办公室。

审批王是云端企业应用软件，类似企业邮箱，不需要安装和维护自己的服务器，打开浏览器就能使用。只需三个步骤，就可以为您的企业开通审批王：
1. 注册审批王账号；
2. 创建企业工作区；
3. 邀请您的同事加入您创建的企业工作区，开始审批。

- [审批王使用指南](workflow/README.md)

### Steedos API

企业使用审批王专业版、企业版时，碰到类似如下的需求场景，建议可调用Steedos API来实现：
- 在HR系统中，需要提请“新员工入职审批”流程（流程都统一部署在审批王系统中）；
- HR系统需要跟踪“新员工入职审批”流程的审批进展；
- HR系统需要接受“新员工入职审批”流程的审批结果，并进行后续处理；
- 登录企业门户Portal/EIP系统后，需要将当前用户在审批王系统中的待办事项进行列表显示;
- 企业数据处理中心，需要导出审批王系统中的审批单的详细信息、并对此进行统计分析、数据挖掘等工作;
- 企业统一组织机构管理（机构、部门、员工等），需要同步到审批王系统；
- 其他业务系统与审批王系统的数据交换。

备注：审批王标准版用户不可以调用Steedos API 。

调用Steedos API，请参考：
- [Steedos API使用指南](api/README.md)
