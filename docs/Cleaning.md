# Cleaning

To properly utilize this module, you will want to have already scraped your data and have the raw dataframe. Once you have your dataframe, simply call clean(df), which returns your dataframe neatly cleaned.

## What clean(df) specifically does:
  - Drop redundant/unnecessary columns
  - Clean html tags from columns with descriptions
  - Set date columns to datetime type
  - Produce "num_verfications" and "num_amenities" columns
  - Clean and casting the "price" column to float
  - Set the true/false columns to boolean type
  - Imputate missing scores
  - Produce wordcount columns
  - Encoded "host_response_time"
  - Turn rates into actual percentages
  - Drop remaining missing values