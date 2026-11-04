# Drama Skills · short-drama-write

> **[short-drama-write](https://github.com/simlpandordinary/short-drama-write)** —— 飞书《WorkBuddy 视频系列 · 全技能与提示词总目录》里推荐的开源技能，已拆分为独立仓库分发（一个技能一个仓库）。

| 项 | 内容 |
| - | - |
| 上游仓库 | <https://github.com/zenstory-ai/drama-skills> |
| 上游路径 | `skills/short-drama-write` |
| 上游协议 | MIT |
| 上游 Star | 3.7k+ |
| 拆分方式 | 仅抽取该技能自身文件，独立可用 |

## 技能说明

编写或修订可拍摄的中文短剧、漫剧单集 Markdown 剧本，也负责保留作者原文并规范化现成剧本。用户提出“写/改一集短剧”“把大纲写成剧本”“优化场景/对白”“去模板感”“去 AI 味润色”“续写下一集”或提供剧本要求进入后续制作时使用；不负责资产、分镜、媒体提示词或终审。

## 目录结构

```
['SKILL.md', 'agents/openai.yaml', 'assets/screenplay.md', 'references/dialogue-craft.md', 'references/production-format-dialect.md', 'references/scene-handoff-capsule.md', 'references/scene-sound-dramaturgy.md', 'references/screenplay-format.md', 'references/script-craft.md', 'references/stage-contract.md', 'references/substitutable-realization.md', 'scripts/duration_estimate.py', 'scripts/screenplay_index.py', 'scripts/selftest.py', 'LICENSE', 'README.upstream.md']
```

- `SKILL.md` 是技能入口（触发条件 / 工作流 / 约束），安装时必须位于技能根目录。
- `references/`、`scripts/`、`assets/` 为该技能自带的参考文档、脚本与素材。
- `README.upstream.md` 为上游仓库原始说明，保留出处与版权信息。
- `LICENSE` 为上游许可证原文。

## 安装

WorkBuddy 技能目录为 `~/.workbuddy/skills/short-drama-write/`：

```bash
git clone https://github.com/simlpandordinary/short-drama-write.git ~/.workbuddy/skills/short-drama-write
```

也可以直接对 AI 说：「把 <https://github.com/simlpandordinary/short-drama-write> 装成 Skill」。

安装后用自然语言触发，例如「Drama Skills · short-drama-write」「用 short-drama-write 帮我处理这个任务」。

本仓库仅含 Drama Skills 技能包中的 `short-drama` 家族技能之一，其余 10 个技能各自独立成仓。

## 版权

原始作者与版权归上游仓库 `zenstory-ai/drama-skills` 所有。本仓库仅做独立分发与结构整理，未修改技能内容；商用请遵循上游许可证。
