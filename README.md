# Finding Predictive Indicators for Wine Ratings

This analysis examines the correlation between wine rating, price, vintage, type, grape variety, and origin of production.

Link to written report: [Final Report](https://docs.google.com/document/d/1vlsi-_8a91J8hdwO1TV4BhKhbJR-QMNDKa__CDiBx58/edit?usp=sharing)

# Metadata

This analysis was conducted using a dataset built with Scrapy. Raw data can be accessed on [this github page.](https://github.com/activatedgeek/winemag-dataset?tab=readme-ov-file). The dataset consisted of 15 rows and 15,460 rows. The following table provides descriptions for each column, including the column name, data type, and an example.

| **Field**  | **Type**  | **Description**  | **Example**  |
|---|---|---|---|
| _alcohol_  | `float64`  | Alcohol by volume (%) |  14.4 |
| _category_ | `string` | Type of wine  | Red  |
| _country_ | `string` | Country of production  | US |
| _description_  | `string` | Written review of wine  | This is a thick, syrupy-rich wine that traffics in candied cherry and oak flavors. It has appeal but lacks varietal character. |
| _designation_  | `string` | Label or title given to wine |  Cuvée  |
| _price_  | `float64` | Price in U.S. dollars ($)  | 28.0 |
| _rating_ | `int64`  | Wine rating between 80 and 100  | 85 |
| _region_  | `string`  | Region within the country of production  | California |
| _subregion_  | `string` | Sub-region within the region of production  | Sonoma  |
| _subsubregion_  | `string`  | Descriptive sub-region of production  | Russian River Valley  |
| _title_  | `string`  | Name of wine  | Merriam 2013 Cuvée Pinot Noir (Russian River Valley)  |
| _url_  | `string`  | Url to review  | [https://www.winemag.com/buying-guide/laurent-...-valley/]([https://www.winemag.com/buying-guide/laurent-gauthier-2016-vieilles-vignes-cote-du-py-morgon/](https://www.winemag.com/buying-guide/merriam-2013-cuvee-pinot-noir-russian-river-valley/)) |
| _varietal_ | `string`  |  Grape/blend varietal | Pinot Noir |
| _vintage_  | `float64`  | Year the grape was harvested  | 2013.0  |
| _winery_  | `string`  | Name of winery  | Merriam  |

# Data Wrangling

As the data was collected through web scraping, some rows contained null, invalid, or incorrect values. 7 deep copies of the initial dataset were created to perform the apporpriate data cleaning and engineering tasks necessary for analysis. Detailed tasks are mentioned in the 'Data Wranling' section of the written report.

# Note

_This analytical project is an extension of my previous assignment from the DATA 11900 Introduction to Data Science course, where my group analyzed factors that influence wine price. Upon review, several errors were found in our approach and analysis. With a deeper understanding of  wine, I have refined the research approach and corrected the errors in data cleaning and analysis._
