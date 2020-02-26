# Data-analytics-for-investment-analysis
## Project Brief
To understand the global trends in investments so that we can take the investment decisions effectively.
### Business and Data Understanding
There are two minor constraints for investments:
1. The amount to be invested is between 5 to 15 million USD per round of investment
2. The amount to be invested only in English-speaking countries because of the ease of
communication with the companies.
! For our analysis, consider a country to be English speaking only if English is
one of the official languages in that country

These conditions will give us sufficient information for our initial analysis. Before
getting to specific questions, let’s understand the problem and the data first.

1. What is the strategy?
 Invest where most other investors are investing. This pattern is
often observed among early stage startup investors.

2. Where did we get the data from?
We have taken real investment data from crunchbase.com, so the insights we get
may be incredibly useful. 
Wou have to use three main data tables for the entire analysis

3. What is the business objective?
The business objectives and goals of data analysis are pretty straightforward.
1. Business objective: The objective is to identify the best sectors, countries,
and a suitable investment type for making investments. The overall strategy is
to invest where others are investing, implying that the 'best' sectors and
countries are the ones 'where most investors are investing'.
2. Goals of data analysis: Your goals are divided into three sub-goals:
  ○ Investment type analysis: Comparing the typical investment amounts
    in the venture, seed, angel, private equity etc. so that Teclov can
    choose the type that is best suited for their strategy.
    
  ○ Country analysis: Identifying the countries which have been the most
    heavily invested in the past. These will be Teclov’ favourites as well.
    
  ○ Sector analysis: Understanding the distribution of investments across
    the eight main sectors. (Note that we are interested in the eight 'main
    sectors' provided in the mapping file. The two files — companies and
    rounds2 — have numerous sub-sector names; hence, you will need to
    map each sub-sector to its main sector.)

3. Sector Classification:
mapping.csv: This file maps the numerous category names in the companies table
(such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The
purpose is to simplify the analysis into eight sector buckets, rather than trying to
analyse hundreds of them.

The findings were presented using three plots, a plot showing the fraction of total investments (globally) in venture, seed, and private equity, and the average amount of investment in each funding type, a plot showing the top nine countries against the total amount of investments of funding type and finally a plot showing the number of investments in the top three sectors of the top three countries on one chart. 

