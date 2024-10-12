#  project 1
> project 1 for ASU AI Bootcamp

This was a team project conducted with 5 classmates altogether.

## Scope and Purpose
Americans are concerned about U.S. Congress persons making profits in the stock market while also having unfair insider information due to their elected positions. Our project would analyze the stock trading activities of U.S. Congress members, with a specific focus on trades disclosed by Nancy Pelosi, because according to social media, the assumptions is that she is a controversially successful person. By examining the dataset of her trades and those of Congress, we intend to uncover potential patterns in stock purchases and sales, identify high-activity sectors, and forecast future trading trends. The project will leverage public disclosures, providing insights into the timing, volume, and market sectors Pelosi and Congress invests in.

## Datasource
We will use Quiver Quantitative as our primary data source: https://www.quiverquant.com/congresstrading/

## Questions we planned to ask of the data
For congress as a whole, is Pelosi even the most interesting person in terms of successful trades? Are there other successful outliers that we should be interested in?
What patterns can be detected in the types of stocks traded by Congress or Pelosi, and are there specific sectors of repeated interest?
How do the timing and frequency of Congress' trades align with significant legislative decisions or market shifts?
Can we use historical data to forecast future trading activity, and what implications might this have for market prediction?
How do Pelosi's stock trades perform relative to major indices like the S&P 500?

## Analysis, Observations and Conclusions

## Installing / Getting started

Open any of the Jupyter notebooks using a Jupyter server. Create a keys.env file with your QuiverQuant API token. Explore the data.

```jupyter lab
retrieve_data.ipynb
```

Run each part of the code in the notebook to explore the data. Note that some of the code is provided to confirm dataset information and to create the requirements for this project.

## Requirements
python version 3.10.14 (main, May  6 2024, 14:42:37) [Clang 14.0.6 ]
pandas version: 2.2.2
requests version: 2.32.3
json version: 2.0.9
also see requirements.txt for dependency details

## Contributing

"If you'd like to contribute, please fork the repository and use a feature
branch. Pull requests are warmly welcome."

