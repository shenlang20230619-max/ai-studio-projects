# 企业AI工程师产品体系 启动指南

## 项目概述
这是一个多页面静态前端项目，展示企业AI工程师完整产品体系，包含首页和三个子产品模块：AI工程师分析系统、AI Workbench产品方案、Agent基础设施架构。

## . - 完整产品展示首页

### 快速启动

由于这是纯静态项目，推荐使用 Live Server 启动：

```bash
npx live-server --port=5500
```

**启动后访问**：
- 首页：http://localhost:5500
- AI工程师分析：http://localhost:5500/1-ai-engineer-analysis/
- AI Workbench：http://localhost:5500/2-ai-workbench/
- Agent基础设施：http://localhost:5500/3-agent-infra/

```yaml
subProjectPath: .
command: npx live-server --port=5500
cwd: .
port: 5500
previewUrl: http://localhost:5500
description: 企业AI工程师完整产品体系展示平台 - 包含首页导航和三个子产品模块
```

## 项目结构说明

- `index.html` - 首页，展示完整产品体系入口
- `1-ai-engineer-analysis/` - AI工程师任务分析与Agent映射关系可视化
- `2-ai-workbench/` - AI Workbench统一工作台产品方案
- `3-agent-infra/` - Agent基础设施分层架构展示
- `assets/` - 静态资源文件
- `docs/` - 文档目录
