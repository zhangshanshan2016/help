# Steedos API

审批王专业版、企业版用户可调用Steedos API，实现如下典型需求：
- 在HR系统中，需要提请“新员工入职审批”流程（流程都统一部署在审批王系统中）；
- HR系统需要跟踪“新员工入职审批”流程的审批进展；
- HR系统需要接受“新员工入职审批”流程的审批结果，并进行后续处理；
- 登录企业门户Portal/EIP系统后，需要将当前用户在审批王系统中的待办事项进行列表显示;
- 企业数据处理中心，需要导出审批王系统中的审批单的详细信息、并对此进行统计分析、数据挖掘等工作;
- 企业统一组织机构管理（机构、部门、员工等），需要同步到审批王系统；
- 其他业务系统与审批王系统的数据交换。

备注：审批王标准版用户不可调用Steedos API 。

### 接口调用说明
- 系统及设置
 - [身份认证](auth.md)
 - [SpaceUser](SpaceUser.md)
 - [Orgnization](Orgnization.md)
- 工作流申请单
 - [Instance](instances.md)
- 工作流设置
 - [Form](Form.md)
 - [Flow](Flow.md)

### 实例
- [Nodejs](sample_nodejs.md)
