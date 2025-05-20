# Data Cleaning and Preparation

## Objectives
- Handle duplicate and missing values
- Normalize text values (lowercase, remove whitestrips, remove special characters)
- Create derived metrics for exploratory analysis:
  - rating_score = rating x rating_count
  - id_discounted
  - price_tier

***

## Database Schema 

ecommerce_data - contains the details for products and brands 

***

## Environment Preparation



***

```python
df['product_name'] = df['product_name'].astype('string')
df['brand_name'] = df['brand_name'].astype('string')
df['product_tag'] = df['product_tag'].astype('string')
df['brand_tag'] = df['brand_tag'].astype('string')
```
