# Ending Image Rules

Column ending images are fixed assets and should be inserted at the end of an article based on the selected column. Do not generate additional fixed text ending by default.

## Mapping

- 《AI 产品落地指南》: `assets/wechat/ending-images/ai-product-guide-ending.png` or `AI_PRODUCT_GUIDE_ENDING_IMAGE_URL_PLACEHOLDER`
- 《书籍推荐》: `assets/wechat/ending-images/book-recommendation-ending.png` or `BOOK_RECOMMENDATION_ENDING_IMAGE_URL_PLACEHOLDER`
- 《热钱之外》: `assets/wechat/ending-images/hot-money-beyond-ending.png` or `HOT_MONEY_BEYOND_ENDING_IMAGE_URL_PLACEHOLDER`
- 《边走边想》: `assets/wechat/ending-images/walking-thinking-ending.png` or `WALKING_THINKING_ENDING_IMAGE_URL_PLACEHOLDER`

If the column is unknown, ask the user to select a column or use `COLUMN_ENDING_IMAGE_URL_PLACEHOLDER` and mark it clearly.

## HTML module

```html
<section style="margin: 32px 8px 0;text-align: center;">
  <img src="COLUMN_ENDING_IMAGE_URL_PLACEHOLDER" style="display:block;width:100%;height:auto;border-radius:12px;" />
</section>
```
