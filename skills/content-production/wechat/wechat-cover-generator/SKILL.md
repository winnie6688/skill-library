---
name: wechat-cover-generator
description: create wechat official account cover concepts and image generation prompts for 要AI不释手. use when the user asks for封面, cover prompt, 配图, 头图, 栏目封面, brand-consistent image prompt, or a cover matching existing examples with minimalist, low-saturation, product-practice visual style.
---

# WeChat Cover Generator

Create cover concepts and image generation prompts. Do not directly copy existing covers; reference their structure, color, spacing, and visual temperament.

## Rules

- Use brand colors and restrained visual tone.
- Keep a strong title, small column label, short subtitle, and right-side product/workflow visual element.
- Avoid neon colors, high-saturation blue-purple, exaggerated people, and marketing-poster style.
- When real reference images are not available, use placeholder rules and clearly mark that visual analysis is pending.

## Output format

1. `# 微信公众号封面生成方案`
2. `## 1. 文章所属栏目`
3. `## 2. 封面主标题`
4. `## 3. 封面副标题`
5. `## 4. 栏目标签`
6. `## 5. 构图说明`
7. `## 6. 配色方案`
8. `## 7. 图像生成提示词`
9. `## 8. 负面提示词`
10. `## 9. 人工检查清单`

## References

- `references/wechat-cover-context.md`
- `references/cover-placeholder-notes.md`
