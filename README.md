# Dataset instructions

Create `data/processed/news_authorship.csv` with columns:
- `text`
- `origin_label` (`human` or `ai`)
- `article_id` (same ID for versions/variants of the same source article)

Keep all variants of an underlying article together when splitting data to avoid leakage. Record dataset provenance and licenses. Do not treat a detector's prediction as ground truth. Authorship labels and factuality labels should be separate in future datasets.
