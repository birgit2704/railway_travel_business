# Railway Travel Business – Country Selection Analysis

## Project Overview

Which country should a railway travel startup choose for its launch?

This project uses data analysis and visualization to make a data-driven recommendation for the company's first market. The dataset contains country-level information on railway infrastructure and usage, GDP, ease of doing business, international tourism, and other economic indicators.

The goal was to identify countries with the strongest combination of **railway demand, railway infrastructure, economic strength, and business conditions**, and ultimately recommend the most promising launch market.

**Final recommendation: France**

## Business Question

The company provided four factors in order of importance:

1. **Current usage of existing railways**
2. **Total length of existing railway infrastructure**
3. **GDP per capita**
4. **Ease of doing business**

Additional questions were considered during the analysis:

* Should railway usage or economic strength carry more weight?
* Does a large railway network necessarily indicate a promising market?
* How important is international tourism for a railway travel business?
* Could geographic proximity to another strong market provide opportunities for future expansion?

## Analytical Approach

I used a step-by-step filtering approach based on the priorities provided by the business.

### 1. Data preparation

The dataset was cleaned and prepared for analysis, including handling inconsistent values and selecting the relevant indicators.

The analysis focused on **2019 data** to provide a consistent pre-pandemic baseline for comparing countries.

### 2. Identify strong railway markets

I first narrowed the dataset to countries with:

* The highest railway usage, measured by passenger distance traveled
* The longest railway networks

This produced a shortlist of **10 countries** that performed strongly on the two most important business criteria.

### 3. Evaluate economic and business conditions

From these 10 countries, I identified the **six strongest performers based on GDP per capita and ease of doing business**.

This additional filtering ensured that the potential market was not only supported by railway demand and infrastructure but also offered a favorable economic and business environment.

### 4. Consider geographic expansion potential

I then examined the geographic distribution of the six remaining countries.

**France and Germany stood out because they share a border.**

This is strategically relevant for a railway travel business: establishing a successful operation in one country could potentially provide a natural path toward expansion into the neighboring market.

### 5. Compare tourism potential

To make the final decision between France and Germany, I considered the number of incoming international tourists.

France receives approximately **5.5 times as many international visitors as Germany**, providing a substantially larger potential market for a tourism-oriented railway travel business.

## Recommendation

### France

Based on the analysis, **France is the recommended country for the startup's launch**.

France combines:

* Strong railway usage
* Extensive railway infrastructure
* Favorable economic conditions
* A strong business environment
* A very large international tourism market
* Geographic proximity to Germany, creating potential for future expansion

The recommendation therefore does not rely on a single metric. Instead, France emerged as the strongest candidate after applying the company's priorities and then considering additional strategic factors.

## Tableau Dashboard & Story

The analysis was developed and presented using Tableau.

**[View the Tableau Story](https://public.tableau.com/app/profile/birgit.bartenschlager/viz/railway_travel_business/Story1)**

**[View the interactive Tableau Dashboard](https://public.tableau.com/app/profile/birgit.bartenschlager/viz/railway_travel_business_dashboard/Dashboard3)**

The Tableau presentation allows the analysis to be explored interactively, including the comparison of railway usage, railway infrastructure, economic indicators, and tourism.

## Key Skills Demonstrated

* Data cleaning and preparation
* Exploratory data analysis
* Multi-factor country comparison
* Translating business priorities into an analytical approach
* Data-driven decision making
* Data visualization
* Dashboard design
* Tableau
* Communicating analytical findings to a non-technical audience

## Conclusion

This project demonstrates how publicly available country-level data can be transformed into a business recommendation.

Rather than optimizing for a single indicator such as GDP or railway size, I followed the priorities established by the business and progressively narrowed the candidate markets. The final decision was then informed by strategic considerations that were not captured by the initial ranking alone—most notably tourism potential and geographic proximity.

**Recommendation: Launch in France, with Germany representing a potential future expansion market.**

