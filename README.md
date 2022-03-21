# :star2:Ames Housing Prices : Directed Exploratory Data Analysis:star2:

This work contains directed exploratory data analysis of Ames Housing Prices dataset, downloaded from Kaggle. The term "directed" refers to the fact that the questions have been pre-determined (by my supervisor at dibimbing.id) and must be answered using EDA. This analysis is carried out in R (Rstudio).

![ide](https://img.shields.io/badge/RStudio-75AADB?style=for-the-badge&logo=RStudio&logoColor=white)
![kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=Kaggle&logoColor=white)

Just in case you didn't know. The codes are contained in the .Rmd (Rmarkdown) file, whereas the results and codes are neatly combined in the .html file (knitted version of Rmarkdown). Feel free to download and open it [here](https://indrayantom.github.io/ames_directedDEA/) 😃😉.

## Objectives
Data used in this work is House Sale Prices in Ames, Iowa, USA from 2006-2010, downloaded from [Kaggle](https://www.kaggle.com/c/house-prices-advanced-regression-techniques). The analysis is carried out to answer these problems :

- Analyze the distribution of target variable SalePrice
- Find 5 variables that are highly correlated to the SalePrice variable
- Analyze the relationship between OverallQuall (material and finish quality) and SalePrice
- Analyze two ‘Haunted Houses’ in GrLivArea vs SalePrice scatter plot (two houses with large ground living area have unnaturally low prices)
- Get one interesting insight from the dataset

## Libraries
This work mainly done using tidyverse environment. However, i also used another libraries to make plots and do certain calculations such as :

- [tidyverse](https://www.tidyverse.org/)
- [gghighlight](https://cran.r-project.org/web/packages/gghighlight/vignettes/gghighlight.html)
- [patchwork](https://patchwork.data-imaginist.com/)
- [ggridges](https://cran.r-project.org/web/packages/ggridges/vignettes/introduction.html#:~:text=The%20ggridges%20package%20provides%20two,then%20draws%20those%20using%20ridgelines.)
- [ggcorplot](https://www.rdocumentation.org/packages/Deducer/versions/0.7-9/topics/ggcorplot)
- [Rmisc](https://www.rdocumentation.org/packages/Rmisc/versions/1.5)
- [grid](https://stat.ethz.ch/R-manual/R-devel/library/grid/html/00Index.html)

## Result preview
According to my hypotheses, the US Economy Crisis had an impact on house sale activity at the time. As a result, this phenomenon could be linked to why there are houses with large ground living area at such low prices.
![preview](https://user-images.githubusercontent.com/92590596/145586144-61ee3f84-26f2-438d-9634-abe93e6c45e2.png)
According to https://www.investopedia.com/terms/g/great-recession.asp , The Great Recession was the sharp decline in economic activity during the late 2000s. It is considered the most significant downturn since the Great Depression. The term Great Recession applies to both the U.S. recession, officially lasting from December 2007 to June 2009, and the ensuing global recession in 2009. The economic slump began when the U.S. housing market went from boom to bust, and large amounts of mortgage-backed securities (MBS’s) and derivatives lost significant value. In Ames however, we get interesting result that that the prices were stagnant during 2006-2010. These years were surely a nightmare for all real estate inventors because the prices didn’t raise year after year.

## References
Below are some references I used to validate my analysis or insights:

- https://www.statista.com/statistics/551403/number-of-vehicles-per-household-in-the-united-states/

- https://slate.com/culture/2008/09/an-economics-mystery-why-houses-cost-more-in-summer-has-finally-been-solved.html

- https://www.investopedia.com/terms/g/great-recession.asp

