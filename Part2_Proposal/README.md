# Project Name: New coffee shop location
#### Problem Statement: What are you trying to solve?
Find a location which would be suitable for a successful new coffee shop. Compare variables such as population and population growth, and locations of currently established coffee shops. The area considered will be the DC Metro area.

#### Data science Hypothesis(es)/solutions considering: One or multiple angles to consider solving this problem with data science  
- Population growth rate
- Average age of the population
- Other coffee shop locations

#### Data sets to be used: Share the links and files, .csvs, .js, .xlsx, .txt, website URLs
- [Yelp Dataset](https://www.yelp.com/dataset)
- [2016 ACS 1-year estimates; Age and Sex](Part2_Proposal/DatasetsForProject/sex_and_age/)
    - This dataset might change or be expanded to include more data; currently the intention is to use it for population data. The data came from [factfinder.census.gov](https://factfinder.census.gov/faces/nav/jsf/pages/download_center.xhtml).

#### Data dictionaries to describe the data types you’re using: write these out in markdown as tables 
- Yelp Dataset - business.json

|Data ID      |Data Type|Data Description                                                           |
|-------------|:-------:|---------------------------------------------------------------------------|
|business_id  |String   |22 character unique string business id                                     |
|name         |String   |the business's name                                                        |
|neighborhood |String   |the neighborhood's name                                                    |
|address      |String   |the full address of the business                                           |
|city         |String   |the city                                                                   |
|state        |String   |2 character state code, if applicable                                      |
|postal code  |String   |the postal code                                                            |
|latitude     |Float    |latitude                                                                   |
|longitude    |Float    |longitude                                                                  |
|stars        |Float    |star rating, rounded to half-stars                                         |
|review_count |Integer  |number of reviews                                                          |
|is_open      |Integer  |0 or 1 for closed or open, respectively                                    |
|attributes   |Object(?)|business attributes to values. note: some attribute values might be objects|
|categories   |Array(?) |an array of strings of business categories                                 |
|hours        |Object(?)|key day to value hours, hours are using a 24hr clock                       |


- 2016 ACS Age and Sex table

|Data ID|Data Type|Data Description|
|-----------------|:-----:|-------------------------------------|
|GEO.id           |String |ID                                   |
|GEO.id2          |String |ID                                   |
|GEO.display-label|String |Display label in format County, State|
|HC01_EST_VC01    |Integer|Estimated total population           |

#### Potential business cases relative to project: how would this help businesses out to make money or save money or improve accuracy or make better products?
This project will allow expanding coffee-shop franchises, as well as entrepreneurs breaking into the coffee shop industry, to find a suitable location for a new coffee shop. By using this analysis, coffee shop owners can avoid opening coffee shops in non-suitable areas, resulting in large savings in capital. Opening a coffee shop in a thriving and expanding area with less competition should also result in higher profits.

#### Potential stakeholders who would find this interesting: who would be your ideal customer or client for this?
Seeing as large franchises like Starbucks already have software which executes this analysis, the ideal customer for this project would be small business owners and prospective entrepreneurs.

#### Potential places to share your results post project (client, world, website, blog)
At this time, I believe the most beneficial method of sharing these results would be through a blog post that would allow the user to reproduce the analysis for different areas (since this will only cover the DC metro area).
