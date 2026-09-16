# Repo Inspiration Scout

一个 Codex Skill：在新项目构思阶段调研公开 GitHub 仓库，筛选三个最值得借鉴的参考项目。

## 能做什么

- 将项目想法拆分为多组检索关键词；
- 从公开 GitHub 仓库中筛选高匹配度候选；
- 阅读 README 和必要的项目文件验证关键功能；
- 用中文提供功能、技术栈、维护情况、许可证、风险与借鉴建议；
- 在候选不足或证据不足时明确说明限制，不用低质量仓库凑数。

## 安装

将本仓库中的 `SKILL.md` 放入个人 Codex 技能目录：

```text
<CODEX_HOME>/skills/github-project-scout/SKILL.md
```

之后在 Codex 中明确调用 `github-project-scout`，或提出“找类似 GitHub 项目”“项目调研”“竞品开源参考”。

## 使用示例

```text
使用 github-project-scout：我想做一个面向独立开发者的 SaaS，自动收集用户反馈、归类问题并生成产品迭代建议。Web 优先，允许 Python 或 TypeScript。
```

Skill 会先在必要时询问关键约束，再返回三个带链接的参考项目和采用建议。

## 注意

结果仅用于调研与借鉴。使用、修改或分发任何项目代码前，请自行核验相应许可证条款。
