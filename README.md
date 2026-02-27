# Energy Consumption Growth in the "AI Era"
Data programming project for UW's CSE 163 with personally selected team. Provides an in-depth analysis and comparison of energy trends and consumption data based on datasets provided by the U.S Energy Information Administration (EIA)

## Research Questions

The Project targets to answer the following questions:

-	How has US energy consumption per capita increased after the “AI Boom” (2022)? 
-	How have projections for energy consumption changed as suddenly more data centers are being built across the country?
-	It is known that energy prices are constantly increasing. However, have energy prices in states with high concentrations of data centers (i.e. Virginia) increased above inflation rates?
---

## Motivation
Issues regarding energy consumption and technology have always been a topic in mainstream news outlets. Some years ago, for example, when Cryptocurrency, NFTs and Blockchain technologies were highly talked about, some issues regarding high energy and water consumption to maintain those structures also became a public debate.

However, in a somewhat unexpected way, another technology surfaced in a much more dramatic way. Since 2022, the quality and multifunctionality of AI and Chatbots have been on the rise, leading to more than half of the US population making daily use of these tools nowadays. This led to more energy consumption, with an average increase of 6.5% in the average cost of electricity for residential customers. However, it is still unclear how much of this was influenced by the construction of more data centers.

The U.S Energy Information Administration (EIA) releases energy production forecasts yearly, based on linear regression models. These, however, cannot predict abnormal events such as technological changes. It is estimated that 4.4% of national energy production goes towards data centers, with some states like Virginia reaching 25%. Therefore, it interests me to find out how the construction of AI datacenters has been shaping energy consumption and prices across the country.

---
## Data Setting

I will be using EIA’s energy dataset, which includes different metrics. I will use the following: 

-	Total energy consumption estimates per capita by end-use sector, annual (https://www.eia.gov/beta/states/data/dashboard/energy-indicators)
-	Average price of electricity to ultimate customers by end-use sector, monthly (https://www.eia.gov/beta/states/data/dashboard/energy-indicators)
-	Annual Energy Outlook 2019 and 2025 (https://www.eia.gov/outlooks/aeo/)

Data sheets are available, and the datasets include state-specific analysis. However, 3 issues may arise:

-	Some of the energy growth might still reflect post-COVID industrial rebound or cryptocurrency mining.
-	National outkast might not reflect the actual growth of AI as data centers are usually highly concentrated in Virginia, Texas, and Iowa.
-	The dataset might be affected by issues such as climate change or immigration (for data that is not related to population growth)
---
For method and code, check `final_project.ipynb`
