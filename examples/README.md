# 优秀案例参考

以下两次完整拆解可作为本 skill 的参考范例（执行拆解时可读取参考其结构与深度，不要复制内容）。

## 谛听（web 端）—— `~/AI/qingnuoditing/`

基于 21 张截图完成的双 Agent（采访 Agent + 写作 Agent）AI 回忆录产品拆解。交付结构：

| 文件 | 对应轮次 |
|------|---------|
| `谛听-拆解图片汇总/`（含图片清单.csv、证据记录.md） | Round 0 |
| `用户旅程图.html` | Round 1 |
| `Agent契约.html` | Round 2 |
| `采访Agent-SystemPrompt.html`、`写作Agent-SystemPrompt.html` | Round 3 |
| `产品全景架构图.html` | Round 4（9 层分层 + ER 图 + 时序图） |
| `谛听-web-拆解汇总.html`、`README.md` | Round 5 |

## 谛听（小程序端）—— `~/AI/qingnuoditing_Mini_program/`

同一产品小程序端的拆解，另含 `谛听全平台拆解汇总.html`（跨端汇总范例）。

## OiiOii

本 skill 各轮提示词最初为拆解 OiiOii（AI 视频生成产品）而写，其提示词原文存于 `~/AI/产品拆解 prompt/prompt_1.txt` ~ `prompt_4.txt`，可对照参考取证粒度与提问方式。

## 使用建议

- 拆解新产品前，可先浏览 `qingnuoditing/用户旅程图.html` 和 `Agent契约.html` 把握交付物的信息密度
- HTML 交付物的视觉风格可对齐谛听案例，保持多轮交付物风格一致
