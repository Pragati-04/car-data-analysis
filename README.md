# Automotive Car Price Analysis (Python + SQL)

I cleaned a car dataset in Python and then used SQL in MySQL to understand the data and find what affects car price.

## Tools Used
- Python (Pandas) – data cleaning and exploratory analysis
- MySQL – SQL queries to understand the data
- Power BI – reporting

## Dataset
- Table name: `cars_clean`
- Total records: 7,785
- Price column: `msrp`
- Columns: make, model, year, engine_fuel_type, engine_hp, engine_cylinders, transmission_type, driven_wheels, number_of_doors, market_category, vehicle_size, vehicle_style, highway_mpg, city_mpg, popularity, msrp

## Project Steps
1. Cleaned the data in Python (Pandas) and saved it as `cars_clean.csv`.
2. Loaded the CSV into MySQL.
3. Renamed columns that had spaces so queries are simple.
4. Wrote SQL queries to answer questions about price, brand, body style and horsepower.

## Questions I Answered with SQL
- How many cars are in the data?
- Which brand has the most and the fewest cars?
- What are the lowest, highest and average prices?
- Which 10 cars cost the most?
- What is the average price of each brand?
- Does fuel type change the price?
- Does body style change the price?
- Do cars with more horsepower cost more?
- Which cars cost more than the average price?
- Which brands have an average price above 15,000?
- Which cars give high horsepower for a low price?

## SQL Used
`SELECT`, `WHERE`, `GROUP BY`, `HAVING`, `ORDER BY`, `CASE`, subquery, `COUNT`, `MIN`, `MAX`, `AVG`, `ALTER TABLE ... RENAME COLUMN`

## Key Findings
- Chevrolet has the most cars (608). Spyker has the fewest (2).
- Prices go from 2,000 to 2,065,902. The average is about 51,028.
- Luxury brands cost the most. Bugatti has the highest average price (about 1.76 million), then Maybach and Rolls-Royce.
- Plymouth has the lowest average price (about 4,189).
- Convertible and Coupe cars cost the most. Hatchbacks and Cargo Minivans cost the least.
- More horsepower means a higher price.
- Fuel type also changes the price.

## Data Quality Note
Many records have the price exactly 2000, and this is also the minimum price. This looks like a default value and not a real price. These rows can make the "high horsepower for low price" result wrong, so they should be checked or left out.

## Files in This Repository
| File | What it is |
|------|------------|
| `Car_Price_SQL_Report.docx` | Full report with all queries and results |
| `cars_clean.csv` | Cleaned dataset |
| `queries.sql` | All SQL queries |

## Author
Pragati Mohalkar
[LinkedIn](https://www.linkedin.com/in/pragati-mohalkar-452878382)
