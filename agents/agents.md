Description：本文档是"任务编排Agent (TOA)"的团队名册和能力索引。TOA通过解析本文档来理解其可指挥的专业Agent团队，并根据任务的关键词将工作分发给最合适的角色。

1. **ArchitectAgent_Enhanced**
   - Core Responsibility: 设计和维护项目的核心技术蓝图，支持任务状态管理和进度反馈
   - Enhanced Features: 架构设计进度报告、技术选型确认、设计决策点报告
   - Keywords (for task matching): 设计, 架构, database, service, workflow, plan,
  structure, 进度, 反馈
   - Use When: 需要实时架构设计进度反馈和人机交互决策

2. **ProductManagerAgent_Enhanced**
   - Core Responsibility: 守护产品的用户价值，支持需求分析进度反馈
   - Enhanced Features: 需求分析进度报告、用户故事确认、验收标准制定报告
   - Keywords (for task matching): 需求, prd, uiux, 澄清, 用户故事, 设计, 进度, 反馈
   - Use When: 需要需求分析过程透明化和设计决策确认

3. **BackendEngineerAgent_Enhanced**
   - Core Responsibility: 实现稳定、高效的后端代码，支持开发进度实时反馈
   - Enhanced Features: 开发里程碑报告、API集成状态、完成预告机制
   - Keywords (for task matching): 后端, 开发, 实现, code, backend, API, 进度, 反馈
   - Use When: 需要后端开发过程可视化和进度监控

4. **FrontendEngineerAgent_Enhanced**
   - Core Responsibility: 构建高质量的用户交互界面，支持UI开发进度反馈
   - Enhanced Features: UI组件完成确认、API集成状态、响应式适配报告
   - Keywords (for task matching): 前端, 界面, 开发, code, frontend, UI, 进度, 反馈
   - Use When: 需要前端开发过程可视化和设计一致性验证

5. **QAAgent_Enhanced**
   - Core Responsibility: 创建全面的测试用例，支持测试设计进度反馈
   - Enhanced Features: 功能分析报告、测试覆盖分析、测试难点识别
   - Keywords (for task matching): 测试, QA, 质量, bug, 验收, 用例, 进度, 反馈
   - Use When: 需要测试设计过程可视化和质量保证监控

6. **ProjectAdminAgent_Enhanced**
   - Core Responsibility: 项目归档和知识管理，支持归档进度反馈
   - Enhanced Features: 历史记录报告、文档索引更新报告、知识沉淀报告
   - Keywords (for task matching): 归档, 索引, 历史, memory, 总结, 规则, 进度, 反馈
   - Use When: 需要项目归档过程可视化和知识管理监控

## Agent选择指南

### 使用原始版本Agent的情况
- 简单任务，不需要复杂的状态管理
- 快速原型开发，不需要详细进度反馈
- 团队已经熟悉现有工作流程
- 项目规模较小，协调需求简单

### 使用增强版本Agent的情况
- 复杂项目，需要精细的任务管理
- 需要实时进度监控和反馈
- 重要的决策点需要人机交互
- 项目规模较大，需要更好的协调和可视化
- 使用增强版TOA进行任务编排

### 混合使用建议
可以在同一项目中根据任务复杂度混合使用不同版本的Agent：
- 核心复杂任务使用增强版本
- 简单辅助任务使用原始版本
- 逐步迁移到全增强版本工作流