---
layout: mapworld
---

# Equality Mapping Project
## By Juan Zumarán
![lgbtq+ flag](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ41Q1pAxI_KhPAm_mv_dr1-1Bh9cKNh86d2A&s)

I created this website with a python notebook, using data from Equaldex, a public API with data for at least 197 countries on LGBT data. 

The goal of this project is to analyze the data from a world perspective, a continent perspective, and an in-depth analysis into the “best” countries to be LGBTQ+ in or travel to, and the “worst” ones. Does the Equality Index vary from country to country visually? How do different continents compare? What can we say about the lowest ranking countries? 
The goal of this project is to build using python notebooks and specifically, the plotly library to create a series of choropleth maps that use the data from the csv obtained from Equaldex’s API. 

# Public Opinion Index
The lower the value, the lower users of the website rank that country. The higher the value, means this country has a lot of upvotes and this is probably because the users feed the website of Equaldex with valuable information. 

How is the index distributed across the continents? can we say something about the overall distributions?

![Box Plots](boxplots.jpg)
Europe has the highest values, while Africa and Asia have a bigger range of values, but overall they both have a lower average than other regions. South America has a lot of high value, and the averge is higher than Europe's, but there are some low scores from some countries.

Europe Map:

![Europe](europe.jpg)

Highlights: Iceland, Norway, Germany, Spain and the Netherlands.


Lowlights: Belarus, Moldova, Bulgaria

South America Map:

![South America](southamerica.jpg)

Highlights: Uruguay, Chile, Brazil, Argentina and Colombia


Lowlights: Paraguay, Guyana and Suriname

North America Map:

![North America](northamerica.jpg)

Highlights: Canada, Mexico, USA and Costa Rica


Lowlights: Haiti, Dominican Republic Panama and Jamaica

Asia Map:
![Asia](asia.jpg)

Highlights: Thailand, Nepal, Japan, India


Lowlights: Russia, Afghanistan, Iran, Oman, Qatar and Brunei

Africa Map:

![Africa](africa.jpg)


Highlights: South Africa and Botswana, 


Lowlights: Somalia, Senegal and Zambia

Oceania Map:
![Oceania](oceania.jpg)


Highlights: Australia, New Zealand and Fiji


Lowlights: Papua New Guinea and Solomon Islands

# Here is an Interactive Map! zoom in, out, pan around or click countries to learn more...


