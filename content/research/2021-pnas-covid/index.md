---
title: "Using Machine Learning to Estimate the Effect of Racial Segregation on COVID-19 Mortality"
Journal: "Proceedings of the National Academy of Sciences"
YearCoauthors: "2021"
id: research
date: "2020-12-10"
SelectedPub: true  # This controls whether is is shown in the Selected Publications section of the home page

linkType: external  # internal  or external
permalinks: https://www.pnas.org/content/118/7/e2015577118


# Summary. An optional shortened abstract.
summary:  This study examines the role that racial residential segregation has played in shaping the spread of the novel coronavirus disease 2019 (COVID-19) in the US as of September 30, 2020. The analysis focuses on the effects of racial residential segregation on mortality and infection rates for the overall population and on racial and ethnic mortality gaps. To account for potential confounding, I assemble a data set that includes 50 county-level factors that are potentially related to residential segregation and COVID-19 infection and mortality rates. These factors are grouped into eight categories (demographics, density and potential for public interaction, social capital, health risk factors, capacity of the health care system, air pollution, employment in essential businesses, and political views). I use double-lasso regression, a machine learning method for model selection and inference, to select the most important controls in a statistically principled manner. Counties that are 1 SD above the racial segregation mean have experienced mortality and infection rates that are 8% and 5% higher than the mean. These differences represent an average of 4 additional deaths and 105 additional infections for each 100,000 residents in the county. The analysis of mortality gaps shows that in counties that are 1 SD above the black-white segregation mean, the black mortality rate is 8% higher than the white mortality rate. Sensitivity analyses show that an unmeasured confounder that would overturn these findings is outside the range of plausible covariates.



btn:
- url : "/research/2021-pnas-covid/2021-pnas-covid-article.pdf" 
  name: pdf
- url : "/research/2021-pnas-covid/2021-pnas-covid-appendix.pdf" 
  name: appendix
- url : "https://doi.org/10.7910/DVN/JHFOSE" 
  name: data
  
# Project  image 
images:
- path: "research/2021-pnas-covid/2021-pnas-covid-image1.png"
  caption: ""
- path: "research/2021-pnas-covid/2021-pnas-covid-image2.png"
  caption: ""  
- path: "research/2021-pnas-covid/2021-pnas-covid-image3.png"
  caption: ""  
  
# Area
area: 
  - Urban Inequality
  - Public Health 

catType: "Journal Articles"
---
This study examines the role that racial residential segregation has played in shaping the spread of the novel coronavirus disease 2019 (COVID-19) in the US as of September 30, 2020. The analysis focuses on the effects of racial residential segregation on mortality and infection rates for the overall population and on racial and ethnic mortality gaps. To account for potential confounding, I assemble a data set that includes 50 county-level factors that are potentially related to residential segregation and COVID-19 infection and mortality rates. These factors are grouped into 8 categories: demographics, density and potential for public interaction, social capital, health risk factors, capacity of the health care system, air pollution, employment in essential businesses, and political views. I use double-lasso regression, a machine learning method for model selection and inference, to select the most important controls in a statistically principled manner. Counties that are 1 SD above the racial segregation mean have experienced mortality and infection rates that are 8% and 5% higher than the mean. These differences represent an average of 4 additional deaths and 105 additional infections for each 100,000 residents in the county. The analysis of mortality gaps shows that in counties that are 1 SD above the black-white segregation mean, the black mortality rate is 8% higher than the white mortality rate. Sensitivity analyses show that an unmeasured confounder that would overturn these findings is outside the range of plausible covariates.



If you are having issues downloading the PDF with the article, [click here]({{< file-download url="/research/2021-pnas-covid/2021-pnas-covid-article.pdf" >}}).

{{< pdfedit src="/research/2021-pnas-covid/2021-pnas-covid-article.pdf" title="Download PDF" height="600" width="90%" >}}

## Appendix

If you are having issues downloading the PDF with the appendix, [click here]({{< file-download url="/research/2021-pnas-covid/2021-pnas-covid-appendix.pdf" >}}).

{{< pdfedit src="/research/2021-pnas-covid/2021-pnas-covid-appendix.pdf" title="Download PDF" height="600" width="90%" >}}

## Replication Files

Data and code are available at [Harvard Dataverse](https://doi.org/10.7910/DVN/JHFOSE).


