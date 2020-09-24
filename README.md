# Malaria Visualization

## Introduction

Malaria is a fatal disease caused by infected mosquitoes. It has remained with human in a long history and is one of the biggest causes of death. Almost half of the world’s population, according to *the World Health Organization* (WHO), is at the risk of catching Malaria. To gain more comprehension about this dreadful epidemic, 3 visualizations are created in this project based on the relevant datasets.

## Datasets

* [`malaria_inc.csv`](./Data/malaria_inc.csv) - Malaria incidence by country for all ages across the world across time.  
* [`malaria_deaths.csv`](./Data/malaria_deaths.csv) - Malaria deaths by country for all ages across the world and time.  
* [`malaria_deaths_age.csv`](./Data/malaria_deaths_age.csv) - Malaria deaths by age across the world and time.  
* [`ne_10m_admin_0_countries`](./Data/ne_10m_admin_0_countries) - A public domain map dataset at 1:10m million scales available at [Natural Earth website](https://www.naturalearthdata.com/).  
* [`data_pop_gdp.csv`](./Data/data_pop_gdp.csv) - The Gross Domestic Product (GDP) per capita and Population for 189 countries in year 2000, 2005, 2010 and 2015.  
* [`region`](./Data/region.csv) - The region of 248 countries.

## Visualization

### Figure 1

The geographic distribution of Malaria based on the deaths caused by this epidemic per 100,000 population from 1990 to 2016 can be visualized as below.

![error](/Gif/map_animation.gif)

The gray part of **Figure 1** means that the Malaria death data for the corresponding countries is not available. Among those without missing data, we can see that the severity of Malaria is greater in the Africa area. Almost all of cases with death number greater than 100 per 100,000 population appear in Africa. This should arise the attention of the corresponding health organizations. Besides, as can be noted, the global death condition in 2015 is much better than that in 1990. This demonstrates the effort made by WHO in containing this epidemic.

### Figure 2

The total number of deaths caused by Malaria in different demographic groups across time is plotted in **Figure 2**.

![error](/Gif/line_animation.gif)

From **Figure 2**, a conclusion can be obtained that children are the most vulnerable object when faced with Malaria, and the level of vulnerability reduces as they grow up according to the lower position of lines with older age. Besides, the total number of deaths for children less than 5 years old is greater than the sum of all the other groups, indicating that infancy is the period that requires more attention during their development stages.

### Figure 3

The relationship between Malaria incidences and GPD per capita in each country across time is shown in **Figure 3**.

![error](/Gif/scatter_animation.gif)

In **Figure 3**, GPD per capita and incidence of Malaria per 1,000 people are converted to logarithmic scale for clearer visualization. The point sizes represent their relative population. Several points are labelled with their country name due to higher population or greater fortune or severer Malaria situation. As is shown, the incidence of Malaria seems to be negatively correlated with the economic condition, indicating that wealthier countries will be less risky in terms of Malaria infection. Besides, the whole group of points slightly move downwards to the right from 2000 to 2015. This might reflect the global improvement in infectious disease control and financial situation.

From the above visualization, a general comprehension can be gained about the dynamic spread and distribution of Malaria. WHO has made a significant progress in containing this epidemic from the global perspective. However, for the eradication of Malaria, there is still a long way to go. In the future, more detailed analysis and visualization might be needed.
