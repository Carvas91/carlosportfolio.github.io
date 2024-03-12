---
title: "Brampton Clustered Businesses Interactive Map"
excerpt: "This project was built in Python and it condenses the Brampton's commercial directory into an interactive map, highlighting proximity and details with a click<br/><img src='/images/rsz_map.png'>"
collection: portfolio
---

I began with the business directory from the Brampton city website, which was in an Excel file. This file had information such as business names, addresses, phone numbers, and their geographic coordinates (longitude and latitude). The first thing I did was clean up this data with Python to make sure it was accurate and ready to use.

Next, I needed to make the geographic coordinates work for my project, so I converted them into a format that let me calculate how far each business was from a central point — the Specsavers location where I used to work.

I chose to use a Python library called 'folium' to create the map. Folium is great for making interactive maps that can show how things are grouped by location. With folium, I put the businesses on the map in such a way that they form clusters based on how close they are to each other. You can click on any cluster to get information about the businesses inside it.

Finally, the Python script I wrote takes all this information and puts it into an HTML file. This file is the interactive map that anyone can use to explore the businesses in Brampton. 
[See Interactive Map](/portfolio/brampton_business_map.html)
[Check the code](https://github.com/Carvas91/Carlos_Vasconez_portfolio/tree/main/Brampton_Interactive_map)


