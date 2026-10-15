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
<img width="1375" height="773" alt="image" src="https://github.com/user-attachments/assets/719285d2-3efb-4227-bc78-033c284428fb" />
<img width="1370" height="688" alt="image" src="https://github.com/user-attachments/assets/9bff02f1-38d4-4ed1-8a30-95518b1e08a9" />
