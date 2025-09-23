# Claude Code Subagents 集合

为 [Claude Code](https://docs.anthropic.com/en/docs/claude-code) 提供专业 AI subagent 的综合集合，在软件开发、基础设施和业务运营方面提供特定领域的专业知识。

## 概览

此存储库提供了扩展 Claude Code 功能的生产就绪subagent，每个都具有专业知识。每个subagent包含：

- 当前行业最佳实践和标准（2024/2025）
- 生产就绪模式和企业架构
- 深度领域专业知识，每个agent具备8-12项能力领域
- 现代技术栈和框架
- 基于任务复杂性的优化模型选择

## agent分类

### 架构与系统设计

#### 核心架构

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [backend-architect](backend-architect.md) | inherit | RESTful API设计、微服务边界、数据库模式 |
| [frontend-developer](frontend-developer.md) | inherit | React组件、响应式布局、客户端状态管理 |
| [graphql-architect](graphql-architect.md) | inherit | GraphQL模式、解析器、联邦架构 |
| [architect-reviewer](architect-review.md) | inherit | 架构一致性分析和模式验证 |
| ~~[cloud-architect](cloud-architect.md)~~ | ~~opus~~ | AWS/Azure/GCP基础设施设计和成本优化 |
| ~~[hybrid-cloud-architect](hybrid-cloud-architect.md)~~ | ~~opus~~ | 跨云和本地环境的多云策略 |
| ~~[kubernetes-architect](kubernetes-architect.md)~~ | ~~opus~~ | 使用Kubernetes和GitOps的云原生基础设施 |

#### UI/UX与移动端

| agent | 模型 | 描述 |
|-------|-------|-------------|
| ~~[ui-ux-designer](ui-ux-designer.md)~~ | sonnet | 界面设计、线框图、设计系统 |
| ~~[ui-visual-validator](ui-visual-validator.md)~~ | sonnet | 视觉回归测试和UI验证 |
| ~~[mobile-developer](mobile-developer.md)~~ | sonnet | React Native和Flutter应用程序开发 |
| ~~[ios-developer](ios-developer.md)~~ | sonnet | 使用Swift/SwiftUI的原生iOS开发 |
| ~~[flutter-expert](flutter-expert.md)~~ | sonnet | 带状态管理的高级Flutter开发 |

### 编程语言

#### 系统与低级编程

| agent | 模型 | 描述 |
|-------|-------|-------------|
| ~~[c-pro](c-pro.md)~~ | ~~sonnet~~ | 带内存管理和OS接口的系统编程 |
| ~~[cpp-pro](cpp-pro.md)~~ | ~~sonnet~~ | 带RAII、智能指针、STL算法的现代C++ |
| ~~[rust-pro](rust-pro.md)~~ | ~~sonnet~~ | 带所有权模式的内存安全系统编程 |
| [golang-pro](golang-pro.md) | inherit | 使用goroutines和channels的并发编程 |

#### Web与应用程序

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [javascript-pro](javascript-pro.md) | inherit | 带ES6+、异步模式、Node.js的现代JavaScript |
| [typescript-pro](typescript-pro.md) | inherit | 带类型系统和泛型的高级TypeScript |
| [python-pro](python-pro.md) | inherit | 带高级功能和优化的Python开发 |
| [ruby-pro](ruby-pro.md) | inherit | 带元编程、Rails模式、gem开发的Ruby |
| [php-pro](php-pro.md) | inherit | 带框架和性能优化的现代PHP |

#### 企业与JVM

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [java-pro](java-pro.md) | inherit | 带流、并发、JVM优化的现代Java |
| ~~[scala-pro](scala-pro.md)~~ | ~~sonnet~~ | 带函数式编程和分布式系统的企业Scala |
| ~~[csharp-pro](csharp-pro.md)~~ | ~~sonnet~~ | 带.NET框架和模式的C#开发 |

#### 专业平台

| agent | 模型 | 描述 |
|-------|-------|-------------|
| ~~[elixir-pro](elixir-pro.md)~~ | ~~sonnet~~ | 带OTP模式和Phoenix框架的Elixir |
| ~~[unity-developer](unity-developer.md)~~ | ~~sonnet~~ | Unity游戏开发和优化 |
| ~~[minecraft-bukkit-pro](minecraft-bukkit-pro.md)~~ | ~~sonnet~~ | Minecraft服务器插件开发 |
| [sql-pro](sql-pro.md) | inherit | 复杂SQL查询和数据库优化 |

### 基础设施与运维

#### DevOps与部署

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [devops-troubleshooter](devops-troubleshooter.md) | inherit | 生产调试、日志分析、部署故障排除 |
| [deployment-engineer](deployment-engineer.md) | inherit | CI/CD管道、容器化、云部署 |
| ~~[terraform-specialist](terraform-specialist.md)~~ | ~~opus~~ | 带Terraform模块和状态管理的基础设施即代码 |
| ~~[dx-optimizer](dx-optimizer.md)~~ | ~~sonnet~~ | 开发者体验优化和工具改进 |

#### 数据库管理

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [database-optimizer](database-optimizer.md) | inherit | 查询优化、索引设计、迁移策略 |
| [database-admin](database-admin.md) | inherit | 数据库运维、备份、复制、监控 |

#### 事件响应与网络

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [incident-responder](incident-responder.md) | inherit | 生产事件管理和解决 |
| [network-engineer](network-engineer.md) | inherit | 网络调试、负载均衡、流量分析 |

### 质量保证与安全

#### 代码质量与审查

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [code-reviewer](code-reviewer.md) | inherit | 注重安全的代码审查和生产可靠性 |
| [security-auditor](security-auditor.md) | inherit | 漏洞评估和OWASP合规 |
| [backend-security-coder](backend-security-coder.md) | inherit | 安全后端编码实践、API安全实现 |
| [frontend-security-coder](frontend-security-coder.md) | inherit | XSS防护、CSP实现、客户端安全 |
| ~~[mobile-security-coder](mobile-security-coder.md)~~ | ~~opus~~ | 移动安全模式、WebView安全、生物识别认证 |
| [architect-reviewer](architect-review.md) | inherit | 架构一致性和模式验证 |

#### 测试与调试

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [test-automator](test-automator.md) | inherit | 综合测试套件创建（单元、集成、e2e） |
| [tdd-orchestrator](tdd-orchestrator.md) | inherit | 测试驱动开发方法指导 |
| [debugger](debugger.md) | inherit | 错误解决和测试失败分析 |
| [error-detective](error-detective.md) | inherit | 日志分析和错误模式识别 |

#### 性能与研究

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [performance-engineer](performance-engineer.md) | inherit | 应用程序分析和优化 |
| [observability-engineer](observability-engineer.md) | inherit | 生产监控、分布式跟踪、SLI/SLO管理 |
| [search-specialist](search-specialist.md) | inherit | 高级网络研究和信息综合 |

### 数据与AI

#### 数据工程与分析

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [data-scientist](data-scientist.md) | inherit | 数据分析、SQL查询、BigQuery操作 |
| [data-engineer](data-engineer.md) | inherit | ETL管道、数据仓库、流式架构 |

#### 机器学习与AI

| agent | 模型 | 描述 |
|-------|-------|-------------|
| ~~[ai-engineer](ai-engineer.md)~~ | ~~inherit~~ | LLM应用、RAG系统、提示管道 |
| ~~[ml-engineer](ml-engineer.md)~~ | ~~inherit~~ | ML管道、模型服务、特征工程 |
| ~~[mlops-engineer](mlops-engineer.md)~~ | ~~inherit~~ | ML基础设施、实验跟踪、模型注册表 |
| [prompt-engineer](prompt-engineer.md) | inherit | LLM提示优化和工程 |

### 文档与技术写作

| agent | 模型 | 描述 |
|-------|-------|-------------|
| [docs-architect](docs-architect.md) | inherit | 综合技术文档生成 |
| [api-documenter](api-documenter.md) | inherit | OpenAPI/Swagger规范和开发者文档 |
| [reference-builder](reference-builder.md) | inherit | 技术参考和API文档 |
| [tutorial-engineer](tutorial-engineer.md) | inherit | 分步教程和教育内容 |
| [mermaid-expert](mermaid-expert.md) | inherit | 图表创建（流程图、序列图、ERD） |

## 安装

将存储库克隆到Claudeagent目录：

```bash
cd ~/.claude
git clone -b model-cn --single-branch \
  https://github.com/Minority2310/claudecode-agents.git agents
```

subagent放置在 `~/.claude/agents/` 目录后将自动可用于Claude Code。

## 使用方法

### 自动委派
Claude Code根据任务上下文和需求自动选择合适的subagent。系统分析您的请求并委派给最合适的专家。

### 显式调用
通过名称指定subagent以使用特定专家：

```
"使用code-reviewer分析最近的更改"
"让security-auditor扫描漏洞"
"让performance-engineer优化这个瓶颈"
```

## 使用示例

### 代码质量与安全
```
code-reviewer: 分析组件的最佳实践
security-auditor: 检查OWASP合规性
tdd-orchestrator: 使用测试优先方法实现功能
performance-engineer: 分析和优化瓶颈
```

### 开发与架构
```
backend-architect: 设计认证API
frontend-developer: 创建响应式仪表板
graphql-architect: 设计联邦GraphQL模式
mobile-developer: 构建跨平台移动应用
```

### 基础设施与运维
```
devops-troubleshooter: 分析生产日志
cloud-architect: 设计可扩展的AWS架构
network-engineer: 调试SSL证书问题
database-admin: 配置备份和复制
terraform-specialist: 编写基础设施模块
```

### 数据与机器学习
```
data-scientist: 分析客户行为数据集
ai-engineer: 为文档搜索构建RAG系统
mlops-engineer: 设置实验跟踪
ml-engineer: 将模型部署到生产环境
```

### 业务与文档
```
business-analyst: 创建指标仪表板
docs-architect: 生成技术文档
api-documenter: 编写OpenAPI规范
content-marketer: 创建SEO优化内容
```

## 多agent工作流

subagent自动协调复杂任务。系统根据任务需求智能地排序多个专家。

### 常见工作流模式

**功能开发**

```
"实现用户认证"
→ backend-architect → frontend-developer → test-automator → security-auditor
```

**性能优化**
```
"优化结账流程"
→ performance-engineer → database-optimizer → frontend-developer
```

**生产事件**
```
"调试高内存使用"
→ incident-responder → devops-troubleshooter → error-detective → performance-engineer
```

**基础设施设置**
```
"设置灾难恢复"
→ database-admin → database-optimizer → terraform-specialist
```

**ML管道开发**

```
"构建带监控的ML管道"
→ mlops-engineer → ml-engineer → data-engineer → performance-engineer
```

### 与Claude Code命令集成

对于复杂的多agent编排，使用 [Claude Code Commands](https://github.com/wshobson/commands) 集合，它提供52个预构建的斜杠命令：

```
/full-stack-feature   # 协调8+个agent进行完整功能开发
/incident-response    # 激活事件管理工作流
/ml-pipeline         # 设置端到端ML基础设施
/security-hardening  # 在整个技术栈中实施安全最佳实践
```

## subagent格式

每个subagent定义为带前言的Markdown文件：

```markdown
---
name: subagent-name
description: 何时应调用此 subagent 的描述
tools: tool1, tool2, tool3  # 可选 - 如果省略，则继承所有工具
model: sonnet | inherit  # 可选 - 指定模型别名 或 继承主 agent 使用的模型
---

您的subagent的系统提示符在这里。这可以是多个段落并且应该清楚地定义subagent的角色、能力和方法来解决问题。

包括具体指示、最佳实践和任何 subagent 应遵循的限制。
```

## agent编排模式

### 顺序处理
agent按顺序执行，向前传递上下文：
```
backend-architect → frontend-developer → test-automator → security-auditor
```

### 并行执行
多个agent同时处理不同方面：
```
performance-engineer + database-optimizer → 合并分析
```

### 条件路由
基于分析的动态agent选择：
```
debugger → [backend-architect | frontend-developer | devops-troubleshooter]
```

### 验证管道
主要工作后跟专门审查：
```
payment-integration → security-auditor → 验证实现
```

## agent选择指南

### 架构与规划

| 任务 | 推荐agent | 关键能力 |
|------|------------------|------------------|
| API设计 | `backend-architect` | RESTful API、微服务、数据库模式 |
| 云基础设施 | `cloud-architect` | AWS/Azure/GCP设计、可扩展性规划 |
| UI/UX设计 | `ui-ux-designer` | 界面设计、线框图、设计系统 |
| 系统架构 | `architect-reviewer` | 模式验证、一致性分析 |

### 按语言开发

| 语言类别 | agent | 主要用例 |
|-------------------|--------|-------------------|
| 系统编程 | `c-pro`, `cpp-pro`, `rust-pro`, `golang-pro` | OS接口、嵌入式系统、高性能 |
| Web开发 | `javascript-pro`, `typescript-pro`, `python-pro`, `ruby-pro`, `php-pro` | 全栈Web应用、API、脚本 |
| 企业级 | `java-pro`, `csharp-pro`, `scala-pro` | 大规模应用、企业系统 |
| 移动端 | `ios-developer`, `flutter-expert`, `mobile-developer` | 原生和跨平台移动应用 |
| 专业化 | `elixir-pro`, `unity-developer`, `minecraft-bukkit-pro` | 特定领域开发 |

### 运维与基础设施

| 任务 | 推荐agent | 关键能力 |
|------|------------------|------------------|
| 生产问题 | `devops-troubleshooter` | 日志分析、部署调试 |
| 关键事件 | `incident-responder` | 中断响应、即时缓解 |
| 数据库性能 | `database-optimizer` | 查询优化、索引策略 |
| 数据库运维 | `database-admin` | 备份、复制、灾难恢复 |
| 基础设施即代码 | `terraform-specialist` | Terraform模块、状态管理 |
| 网络问题 | `network-engineer` | 网络调试、负载均衡 |

### 质量与安全

| 任务 | 推荐agent | 关键能力 |
|------|------------------|------------------|
| 代码审查 | `code-reviewer` | 安全焦点、最佳实践 |
| 安全审计 | `security-auditor` | 漏洞扫描、OWASP合规 |
| 测试创建 | `test-automator` | 单元、集成、E2E测试套件 |
| 性能问题 | `performance-engineer` | 分析、优化 |
| Bug调查 | `debugger` | 错误解决、根因分析 |

### 数据与机器学习

| 任务 | 推荐agent | 关键能力 |
|------|------------------|------------------|
| 数据分析 | `data-scientist` | SQL查询、统计分析 |
| LLM应用 | `ai-engineer` | RAG系统、提示管道 |
| ML开发 | `ml-engineer` | 模型训练、特征工程 |
| ML运维 | `mlops-engineer` | ML基础设施、实验跟踪 |

### 文档与业务

| 任务 | 推荐agent | 关键能力 |
|------|------------------|------------------|
| 技术文档 | `docs-architect` | 综合文档生成 |
| API文档 | `api-documenter` | OpenAPI/Swagger规范 |
| 业务指标 | `business-analyst` | KPI跟踪、报告 |
| 法律合规 | `legal-advisor` | 隐私政策、服务条款 |

## 最佳实践

### 任务委派
1. **自动选择** - 让Claude Code分析上下文并选择最佳agent
2. **明确需求** - 指定约束、技术栈和质量标准
3. **信任专业化** - 每个agent都针对其特定领域进行了优化

### 多agent工作流
1. **高级请求** - 允许agent协调复杂的多步任务
2. **上下文保持** - 确保agent具有必要的背景信息
3. **集成审查** - 验证不同agent的输出如何协同工作

### 显式控制
1. **直接调用** - 在需要特定专业知识时指定agent
2. **战略组合** - 使用多个专家进行验证
3. **审查模式** - 请求特定的审查工作流（例如"security-auditor审查API设计"）

### 性能优化
1. **监控效果** - 跟踪哪些agent最适合您的用例
2. **迭代改进** - 使用agent反馈改进需求
3. **复杂性匹配** - 将任务复杂性与agent能力对齐

## 贡献

要添加新的subagent：

1. 创建带适当前言的新`.md`文件
2. 使用小写、连字符分隔的命名约定
3. 在描述中编写清晰的激活条件
4. 定义带专业领域的综合系统提示

## 故障排除

### agent未激活
- 确保请求明确指示领域
- 具体说明任务类型和需求
- 如果自动选择失败，使用显式调用

### 意外的agent选择
- 提供更多关于技术栈的上下文
- 在请求中包含具体需求
- 使用直接agent命名进行精确控制

### 冲突建议
- 正常行为 - 专家有不同的优先级
- 请求特定agent之间的协调
- 根据项目需求考虑权衡

### 缺少上下文
- 在请求中包含背景信息
- 引用先前的工作或模式
- 提供项目特定的约束

## 许可证

MIT许可证 - 详见 [LICENSE](LICENSE) 文件。

## 资源

- [Claude Code文档](https://docs.anthropic.com/en/docs/claude-code)
- [subagent文档](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)
- [Claude Code Commands](https://github.com/wshobson/commands)
