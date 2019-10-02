# Project1Final

Project 1: EDA on MTA Turnstile Data

### Background
WomenTechWomenYes(WTWY) reached out to Metis in NYC. They are interested in "harnessing the power of data and analytics to optimize the effectiveness of our street team work, which is a significant portion of our fundraising efforts." Excerpt from their letter:

> WomenTechWomenYes (WTWY) has an annual gala at the beginning of the summer each year. As we are new and inclusive organization, we try to do double duty with the gala both to fill our event space with individuals passionate about increasing the participation of women in technology, and to concurrently build awareness and reach. To this end we place street teams at entrances to subway stations. The street teams collect email addresses and those who sign up are sent free tickets to our gala.

The task is to use freely available MTA subway data from the city to help WTWY optimize the placement of street teams, to gather the most signatures, ideally from those who will attend the gala and contribute to the cause.

### Objectives
Perform Exploratory Data Analysis (EDA) on MTA data to:

* Find stations with the highest weekly traffic in May and June 2019
* Identify stations most likely to attract people who are:
  - Women working in or studying technology
  - Interested in increasing participation of women in tech

### Data
MTA Turnstiles data (MTA)

Subway station locations - geographic (NYC OpenData)

Additional geographical data:

* Location of colleges and universities (NYC OpenData)

* Location of tech companies (NYC OpenData)

### Tools
Python, Pandas, NumPy

Matplotlib, Seaborn, GeoPandas

GitHub

### Results

Based on results of our analysis as well as domain knowledge of NYC, we recommended 15 stations in Manhattan with highest volumne of traffic. Among those, our top 3 recommendations are stations with universities clustered around them. We visualized these results using Seaborn and Geopandas.

### Further Work

Scraping geographical data of tech companies, algorithmically compare top stations based on how many tech companies and universities are within a set radius to each.

### Division of Tasks
- data collection (f, d)
- data cleaning (l)
- visualization 
  - seaborn visualization (f)
  - geopandas (d)
- GitHub repo setup and maintenance (f, d)
- presentation slides (f)
- project design, outline (all)
- organizational/logistics/"project manager" role (f)
