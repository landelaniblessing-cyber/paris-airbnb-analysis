# Paris Airbnb Analysis

What drives Airbnb prices in Paris?

## Dataset
- Source: Airbnb Listings dataset from Kaggle (Listings.csv)
- Original: 279,712 listings from cities worldwide
- After filtering to Paris (lat 48.8-48.92, lon 2.2-2.5): 64,690 listings
- After cleaning prices ($10 - $1,000): 64,410 listings

## Key Findings
- Median price in Paris: $80 per night (Mean: $106)
- Room Type: Hotel room $160, Entire place $82, Private room $53, Shared room $34
- Most expensive neighbourhoods: Elysee ($125), Louvre ($115), Hotel-de-Ville ($109), Luxembourg ($107)
- Size matters most: 1 guest $45, 2 guests $69, 4 guests $99, 6 guests $145
- Superhosts charge $92 vs $80 for non-Superhosts (only 13% are Superhosts)
- Reviews do NOT drive price: correlation only 0.04

## Tools
Python, pandas, matplotlib in Kaggle Notebook

## Files
- `notebook881e2ea07c.ipynb` - Full analysis with code and charts
