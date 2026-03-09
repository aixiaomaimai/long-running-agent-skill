# long-running-agent Skill

[![Version](https://img.shields.io/badge/version-3.0.Lite-blue)](https://github.com/aixiaomaimai/long-running-agent-skill/releases)
[![OpenClaw](https://img.shields.io/badge/OpenClaw-2026.3.0+-green)](https://openclaw.ai)
[![License](https://img.shields.io/badge/license-MIT-yellow)](LICENSE)

> 基于 Anthropic 研究《Effective harnesses for long-running agents》实现的长周期代理架构

---

## 🎯 核心特性

- 两阶段 ONBOARDING（Phase 1 探索 + Phase 2 执行）
- 自动学习改进（纠正/错误/功能请求检测）
- 智能依赖检测（方案 C：不冗余复制）
- 任务拆解、环境验证、E2E 检查、HITL 验证
- Git 版本控制

---

## 🚀 快速安装

```bash
# 1. 下载发布包
wget https://github.com/aixiaomaimai/long-running-agent-skill/releases/download/v3.0.Lite/skill-3.0-lite-*.tar.gz

# 2. 解压安装
tar -xzf skill-3.0-lite-*.tar.gz
cd skill-3.0-lite-*/
bash install.sh

# 3. 验证
bash test.sh
