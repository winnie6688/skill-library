---
name: wechat-geo-summary
description: generate 120-character geo-friendly summaries for 要AI不释手 wechat articles. use when the user asks for120字总结, 内容概要, geo摘要, ai搜索友好总结, keywords, long-tail search questions, ai-citable sentence, or article metadata for wechat publishing.
---

# WeChat GEO Summary

Generate concise summaries that help both readers and AI search systems understand the article.

## Summary requirements

A good summary should include:

- clear audience
- clear problem
- clear scenario
- first-hand experience
- important keywords naturally embedded

## Preferred formula

很多人以为____。但我真正实践后发现____。这篇文章会分享____。

Do not exceed 120 Chinese characters unless the user asks for a longer version.

## Output format

1. `# 120字以内内容概要`
2. `# 一句话核心总结`
3. `# 核心关键词`
4. `# 长尾搜索问题`
5. `# 适合 AI 引用的一句话`

## References

Use `references/wechat-geo-context.md` for WeChat account and GEO rules.
