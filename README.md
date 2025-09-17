# GLCC结项 PR汇总

本文件汇总了本次glcc的相关 PR，用于汇报和追踪

## Casbin 核心

核心功能修复与优化。

- [casbin PR #1504](https://github.com/casbin/casbin/pull/1504) - 修复Enforcer无法正常获取ConditionalRoleManager的问题，并实现缺失方式。

## 支持 Biba Model

实现 Biba 模型及演示。

- [casbin PR #1520](https://github.com/casbin/casbin/pull/1520) - casbin支持Biba模型。
- [casbin-editor PR #245](https://github.com/casbin/casbin-editor/pull/245) - 添加Biba模型的演示。
- [casbin-website-v2 PR #290](https://github.com/casbin/casbin-website-v2/pull/290) - 更新 Biba 模型相关文档 。

## 支持 UCON Model

实现 UCON 模型及相关功能。

- [casbin-ucon PR #2](https://github.com/casbin/casbin-ucon/pull/2) - 添加初始代码。
- [casbin-ucon PR #3](https://github.com/casbin/casbin-ucon/pull/3) - 实现基本的 UconEnforcer，包含测试和 CI 配置。
- [casbin-ucon PR #5](https://github.com/casbin/casbin-ucon/pull/5) - 修复 semantic-release CI。
- [casbin-ucon PR #6](https://github.com/casbin/casbin-ucon/pull/6) - 添加会话管理器并更新 README 。
- [casbin-website-v2 PR #298](https://github.com/casbin/casbin-website-v2/pull/298) - 文档更新

## 汇总说明

- 修复核心bug，实现对 Biba 与 UCON 模型的支持并有示例演示。
- 文档同步更新，便于团队及社区参考。