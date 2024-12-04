# Dataset Datasheet: Analysis Data

## Dataset Overview
- **Name**: Canadian Grocery Price Data
- **Source**: [\[Jacob Filipp\]](https://jacobfilipp.com/hammerdata/hammer-5-csv.zip)
- **Version**: 1.0
- **Licensing**: Open License

## Data Collection
- **Collection Method**: Downloaded the data from the site.
- **Date Range**: 28th February 2024-28th November 2024
- **Sampling Method**: Data collected from Voila, T&T, Loblaws, No Frills, Metro, Galleria, Walmart Canada, and Save-On-Foods grocery stores over 9 months.

## Data Structure
- **Columns**:
    Column	Description
- `nowtime`:	Timestamp indicating when the data was gathered
- `vendor`:	One of the 7 grocery vendors
- `product_id`:	An internal ID for a product - it represents 1 unique product at 1 vendor.
- `product_name`:	Product name. May include Brand, may include Units in it.
- `brand`:	Brand name. May be blank for some vendors.
- `units`:	Units (grams, kg, number of items in package). May be blank for some vendors/products.
- `current_price`:	Price at time of extract
- `old_price`:	An "old" struck-out price. This indicates that there was a Sale on.
- `price_per_unit`: Price per unit, as shown on the vendor website.
- `other`:	Other details that appeared on the listing. Values may be "Out of stock", "SALE", "Best seller", "$5.00 MIN 2"

## Missing Data
- Missing values were handled by filling with the median or removing incomplete records.

## Potential Risks
- No Privacy concerns with consumer data.
