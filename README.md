# Bank Marketing Analysis

Dataset: Bank marketing campaign.
Goal: understand which customers subscribe to a term deposit.

## Cleaning steps
- Replaced pdays = 999 with NaN, added was_contacted_before
- Created subscribed_flag (0/1) from y
- Kept "unknown" as its own category (different behaviour)
- Removed 12 duplicate rows
- Added age_group, campaign_group, month_num, duration_min

## Key findings
- Deposit rate: 11.3% overall
- More calls = lower rate
- Students, retired and 65+ subscribe most

## Next
- Tableau dashboard
- Model (duration excluded: data leakage)
