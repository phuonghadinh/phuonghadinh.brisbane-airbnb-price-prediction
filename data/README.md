# Data

The listing files are **not included** in this repository. They were provided through a class Kaggle competition and are based on [Inside Airbnb](https://insideairbnb.com/) data for Brisbane.

## Files needed

| File | Contents |
|---|---|
| `train.csv` | 3,735 listings with 65 fields, including `price` (the target) |
| `test.csv` | 1,601 listings with the same fields except `price` |

Place both files in this `data/` folder before running the notebooks:

```
data/
├── train.csv
├── test.csv
└── README.md
```

## Key fields

| Group | Fields |
|---|---|
| Location | `latitude`, `longitude`, `neighbourhood_cleansed` |
| Listing | `property_type`, `room_type`, `accommodates`, `bedrooms`, `beds`, `bathrooms_text`, `amenities` |
| Host | `host_is_superhost`, `host_since`, `calculated_host_listings_count`, `instant_bookable` |
| Reviews | `review_scores_rating` and six sub-scores, `number_of_reviews` |
| Demand | `estimated_occupancy_l365d` (nights booked, last 12 months), `estimated_revenue_l365d` |
| Target | `price` (nightly price, text such as `$193.00`) |
