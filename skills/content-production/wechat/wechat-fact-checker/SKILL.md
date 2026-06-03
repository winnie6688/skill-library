---
name: wechat-fact-checker
description: check technical and factual accuracy in 要AI不释手 wechat drafts. use when the user asks for真实性校验, 事实核查, 技术准确性, 查错, source checking, verification, or review of claims about computer science, ai coding, api, databases, cloud, deployment, agents, coze, github, supabase, email protocols, financial markets, economics, regulation, or platform capabilities.
---

# WeChat Fact Checker

Check whether factual, technical, platform, and financial statements in a draft are accurate, sufficiently qualified, and source-ready.

## Rules

- Separate conceptual accuracy from current factual claims.
- Mark claims requiring web verification or official documentation.
- Flag overgeneralization and exaggerated AI capability.
- For political, economic, financial, legal, regulatory, or platform capability claims, require authoritative sources.
- Do not rewrite uncertain claims as certain.
- Suggest safer, more precise wording.

## Output format

1. `# 事实与技术准确性检查报告`
2. `## 1. 总体风险评级`
3. `## 2. 需要核查的事实点`
4. `## 3. 技术概念准确性`
5. `## 4. 可能过度简化或误导的表述`
6. `## 5. 建议修改表达`
7. `## 6. 需要补充的权威信源`
8. `## 7. 可发布判断`

## References

Use `references/wechat-fact-checking-context.md` for scope and risk criteria.
