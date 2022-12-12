# Housing Market in Ontario

## Poject 1 - Team 12: 
###### Andreza dos Santos 
###### Chu Nguyen Kien
###### Sameen S
###### Instructor: Faye

## Objective of the project
As a new family finding a new home and wanting to raise kids in Canada there are many factors that must be met. Ontario came up as an ideal location due to its bustling environment and opportunities for growth. But which city is the best suited for a young family in Ontario?

Every family most likely will say that the amenities around the area such as schools, healthcare locations, and daycares are key considerations in any case. For this reason we've decided to analyse not only the prices but also the neiboughood.

## Major Questions
- What are the TOP Housing Markets in Ontario? 
- How do these prices fluctuate between different cities in Ontario?
- How do these prices fluctuate between GTA?
- Expensive vs Cheapest areas to buy a House within GTA.
- How do Amenities contribute to the inflated House prices in and around GTA?

## Datasource
https://www.kaggle.com/datasets/mnabaee/ontarioproperties

## Description of Data Analysis 
Data Analysis was done in a 3 step process.
  - Step 1: Applied the Extract, transform, load process to the data source.
  - Step 2: Created Visuals through Matplotlib.
  - Step 3: Make a presentation through PowerPoint

## TOP 20 Rank by area with highest # of houses sold in ONTARIO
![Picture1](https://user-images.githubusercontent.com/114877740/207099505-2e9303a6-12ae-4ea2-9966-e9a65a8e363d.png)

## TOP 20 Rank by area with highest average price in ONTARIO
![Picture2](https://user-images.githubusercontent.com/114877740/207099862-8b47dbf7-cae2-4f8e-b558-df88cbac50d2.png)

## TOP 20 Rank by area - OUTLIERS
![Picture3](https://user-images.githubusercontent.com/114877740/207100299-d36d0f59-5ccd-4360-a5b1-2bc81b17f81c.png)

## Housing Market in TORONTO & GTA
As GTA had the highest number of homes sold in the period, we decided to focus our analysis on this area.

# Toronto

## Top 20 highest average prices by Area in TORONTO
On the following Map Plot you will find the top 20 rank of the most expensive areas in Toronto, where each color is related to an area and the size of circles follows the average price.

![top20-toronto](https://user-images.githubusercontent.com/114877740/207148479-0a59b39a-bf87-4071-a828-4f92661f6a53.png)

## Bottom 20 smallest average prices by Area in TORONTO
On the following Map Plot you will find the bottom 20 rank of the cheapest areas in Toronto, where each color is related to an area and the size of circles follows the average price.

![bottom20-toronto](https://user-images.githubusercontent.com/114877740/207148541-326eea80-4ec8-40b6-a839-041f0ac22157.png)

# GTA - Excluding Toronto

## Top 20 highest average prices by Area in GTA
On the following Map Plot you will find the top 20 rank of the most expensive areas in GTA, where each color is related to an area and the size of circles follows the average price.

![top20-GTA](https://user-images.githubusercontent.com/114877740/207148612-e96dae45-f6f8-4599-9618-f80c58a0872a.png)


## Bottom 20 smallest average prices by Area in GTA
On the following Map Plot you will find the bottom 20 rank of the cheapest areas in GTA, where each color is related to an area and the size of circles follows the average price.

![bottom20-GTA](https://user-images.githubusercontent.com/114877740/207148654-2029cbb8-0d08-46fe-9dd1-054c4c9da649.png)

# Amenities

In order to analyze the amenities available in each neighborhood, we've considered the following parameters:
- Data: Top 5 highest average price in Toronto & GTA and bottom 5 smallest prices.
- API: https://www.geoapify.com/
- Radius: 10km
- Categories: education.school, childcare and healthcare

## Amenities - Toronto
As per showing below, for areas located in Toronto, there too many amenities around not only on the most expensive areas but also on the cheapest ones. 

We have highlighted the nearest School, Daycare and Healthcare for each address and also demostrated through a pie chart the number or amenities available in each area.

###### Toronto - Data

![Picture8](https://user-images.githubusercontent.com/114877740/207108572-1d3cba88-59c5-47f9-ba31-0566dc4fe4e1.png)

###### Toronto - Pie Chart


![fig5](https://user-images.githubusercontent.com/114877740/207108892-5885a78f-3d0b-466b-ab2a-e1c5c8c0d592.png)

![fig6](https://user-images.githubusercontent.com/114877740/207108924-37773b68-37bc-4179-949c-8b7ea31a2d0c.png)

![fig7](https://user-images.githubusercontent.com/114877740/207108941-cc48802e-86bd-4430-99cd-f986d0126a72.png)

## Amenities - GTA
As per showing below for GTA (excluding Toronto), there are schools availables for all areas. However, only 2 of them have daycares and hospitals which are the the post expensive areas. The cheapest ones, which are located in a rural area or more upnorth.

We have highlighted the nearest School, Daycare and Healthcare for each address and also demostrated through a pie chart the number or amenities available in each area.

###### GTA - Data

![fig8](https://user-images.githubusercontent.com/114877740/207111311-0ef49421-c336-4472-8b0b-345019808a4b.png)

###### GTA - Pie Chart

![fig9](https://user-images.githubusercontent.com/114877740/207111402-a2e801c3-31f5-4ea3-b87d-a02b76916cbc.png)

![fig10](https://user-images.githubusercontent.com/114877740/207111420-55cf6475-e4f0-45a8-bc6b-b6bb1fdc02c8.png)

![fig11](https://user-images.githubusercontent.com/114877740/207111429-79165ea8-9c4f-47ca-a567-f383c8ec9b68.png)

# Top prices vs Bottom Prices

This is just an overview about the variances between the most expensive and cheapest prices for Toronto and GTA.

###### Toronto
###### > Min Price: $115,000.00	
###### > Max Price: $9,688,000.00

![fig12](https://user-images.githubusercontent.com/114877740/207115220-66f3f8af-e963-498f-9c95-aab1fa877c77.png)

###### GTA
###### > Min Price: $210,000.00 
###### > Max Price: $9,000,000.00

![fig13](https://user-images.githubusercontent.com/114877740/207115292-6ff6956f-0091-421b-96a5-cf34332f7650.png)

# Correlation

This top show if there is any correlation between the prices and the amenities available in neighborhood. 

###### Toronto: MODERATE correlation (0.69) between both as per showing following

![Picture10](https://user-images.githubusercontent.com/114877740/207117175-429471c1-e4f5-41a6-9613-8ab6e61a21d4.png)

###### GTA: STRONG correlation (0.82) between both as per showing followin

![Picture11](https://user-images.githubusercontent.com/114877740/207117349-7aa1c33c-3a36-46e2-9066-8385fe42f901.png)

# Conclusion

- GTA had the highest number of houses sold in the period comparing with other areas.
- All the areas within Toronto have many amenities available.
- The cheapest areas in GTA do not have healthcare or daycare within 10km radius.
- More amenities = Higher price
