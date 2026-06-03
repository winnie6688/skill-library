# WeChat HTML/CSS Layout Context

## Layout goal

Generate HTML/CSS that can be copied into WeChat Official Account editors or tools such as 壹伴. The style must match the brand identity of 要AI不释手: clean, restrained, low-saturation, trustworthy, and suitable for long-form reading.

## Compatibility rules

- Use inline CSS.
- Prefer stable `section + p` structures.
- Avoid deeply nested complex HTML.
- Prefer card-style comparison blocks over `<table>` when possible.
- Every card module must include background color, padding, border or border-left, and border-radius.
- Use mobile-first readability.

## Fixed color tokens

- Page background: #F7F6F3
- Body text: #2F3437
- Primary brand: #8DAA91
- Highlight text: #66786B
- Light card background: #EEF1EC
- Core idea background: #E7ECE6
- Method module background: #F3F5F1
- Divider: #DDE2DA
- Annotation text: #6B6B6B

## Typography

- Body font size: about 15px.
- Line height: about 1.8-1.95.
- Letter spacing: about 0.5-2px depending on module.
- Keep paragraphs short.

## Preferred modules

- reading info
- summary module
- normal paragraph
- section heading
- quote/core idea card
- method/checklist card
- normal information card
- card-style comparison block
- image module
- fixed column ending image module

## Ending image rule

Each column uses a fixed ending image. Do not generate a fixed text ending by default. Use placeholders until real image URLs are supplied.
