# Dashboarding
This is an example of an interactive dashboard that scrapes & cleans data requested by the user. 
Uses the `voila` package to present dashboard. Go to directory of "Dash.ipynb", and run `voila Dash.ipynb` to see results or follow through the notebook.

## Fields

* City: the city of interest, scraped from "insideairbnb.com"
* Display: 
  * `head`: render the first 5 rows
  * `tail`: render the last 5 rows
  * `random`: render 5 random rows
* Preprocessed:
  * `True`: data is preprocessed
  * `False`: data is as directly scraped
