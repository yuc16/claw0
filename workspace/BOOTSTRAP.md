# 启动上下文

这个文件提供智能体启动时加载的额外上下文。

## 项目背景

这个智能体属于 claw0 教学框架的一部分，用来演示如何从零构建一个 AI 智能体网关。`workspace` 目录中的配置文件会共同塑造智能体的行为：

- SOUL.md：人格与沟通风格
- IDENTITY.md：角色定义与边界
- TOOLS.md：可用工具与使用说明
- MEMORY.md：长期事实与偏好
- HEARTBEAT.md：主动行为指令
- BOOTSTRAP.md：本文件，提供额外启动上下文
- AGENTS.md：多智能体协作说明
- CRON.json：定时任务定义

## 工作区结构

```text
workspace/
  *.md          -- 启动文件（加载进 system prompt）
  CRON.json     -- 定时任务定义
  memory/       -- 每日记忆日志
  skills/       -- 技能定义
  .sessions/    -- 会话记录（自动管理）
  .agents/      -- 每个智能体的状态（自动管理）
```
