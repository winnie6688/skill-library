# Skill Library

这是 Lyra 的个人 Skill 合集仓库，用于收录、管理和迭代在 ChatGPT 中使用的自定义 Skills。

这个仓库会保存不同场景下的 Skill 源码、打包文件、使用说明和版本记录，覆盖内容生产、知识资产沉淀、飞书多维表格、邮件处理、事实校验、AI 工作流等方向。

## Current collections

### WeChat Official Account Skill Group V1-alpha

用于「要AI不释手」微信公众号内容生产流程，包括品牌上下文、正文润色、标题生成、HTML/CSS 排版、封面提示词、GEO 摘要、事实校验和发布前检查。

| Skill | 用途 |
|---|---|
| `wechat-brand-context` | 微信公众号品牌上下文 |
| `wechat-content-polisher` | 正文润色与结构优化 |
| `wechat-title-generator` | 标题生成与优化 |
| `wechat-html-css-layout` | 公众号 HTML/CSS 排版 |
| `wechat-cover-generator` | 封面图提示词生成 |
| `wechat-geo-summary` | 120 字 GEO 友好摘要 |
| `wechat-fact-checker` | 技术事实与现实规则校验 |
| `wechat-publish-checker` | 发布前总复核 |

## Repository structure

```text
skill-library/
├── README.md
├── docs/
├── skills/
├── dist/
├── templates/
└── CHANGELOG.md
```

## Usage

1. Go to `dist/` and download the target Skill zip.
2. Upload the zip to ChatGPT Skills.
3. Use the corresponding trigger phrase in conversation.
4. If a Skill output is unstable, update the source files in `skills/` and rebuild the zip.
