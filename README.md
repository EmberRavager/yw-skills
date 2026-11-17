# yw-skills

一组个人维护的 Codex Skills，把学习新知识、阅读论文和设计前端界面的方法整理成可以重复使用的流程。

## Skills

| Skill | 用途 | 状态 |
| --- | --- | --- |
| [`learn`](skills/learn/SKILL.md) | 学习新主题或读论文。用三句话和知识关系图讲清核心，再通过例子和追问逐步深入。 | 可用 |
| [`design`](skills/design/SKILL.md) | 设计或重做前端界面。从主题取材，比较三个设计方向，定下配色、字体和布局，再实现并自检。 | 可用 |
| [`dev`](skills/dev/SKILL.md) | 实现功能、扩展能力或重构代码。 | 仅有名称和描述 |
| [`fix`](skills/fix/SKILL.md) | 定位和修复 Bug、失败测试或回归。 | 仅有名称和描述 |
| [`prompt`](skills/prompt/SKILL.md) | 编写或修改 Agent、系统及 Workflow 节点提示词。 | 仅有名称和描述 |
| [`review`](skills/review/SKILL.md) | 审查 PR、分支和未提交的代码变更。 | 仅有名称和描述 |

## 在 Codex 中安装

把要安装的那一行粘贴到 Codex 的输入框。

```text
$skill-installer install https://github.com/EmberRavager/yw-skills/tree/main/skills/learn
$skill-installer install https://github.com/EmberRavager/yw-skills/tree/main/skills/design
```

安装后，在新对话中输入 Skill 名称和任务。如果选择器里没有出现新 Skill，重启 Codex。

```text
$learn 带我理解 Transformer，从一个可以手推的例子开始。
$design 为工具执行日志做一个桌面和手机都能用的页面，主要任务是快速找到失败原因。
```
