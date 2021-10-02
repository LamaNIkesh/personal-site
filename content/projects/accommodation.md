---
title: "Identification of Ideal Locations for Student Accommodation"
date: '2021-08-17T14:55:11.373Z'
description: "Something somethings"
draft: false
#categories: ["Data science"]
tags: 
- Pandas
- EDA
- Folium
- Foursquare
- Cluster analysis
---



> This is part of my IBM data science course I completed using Folium, Foursquare API, Scikit-learn and Pandas — plus other necessary libraries such as Matplotlib, numpy etc. Complete Jupyter notebook on NBViewer is available [here](https://nbviewer.jupyter.org/github/LamaNIkesh/Coursera_Capstone/blob/87a56fb0b9ca29576d4a1d32bb9a6148d8e45269/Capstone_Uni_accommodation_final.ipynb) for rendered experience. Also, the notebook can be viewable on my [github](https://github.com/LamaNIkesh/Coursera_Capstone/blob/main/Capstone_Uni_accommodation_final.ipynb) as well, however some figures may not render properly.



{{< figure src="/images/project1/clusters.png" width="600px" class="center">}}



### Business Problem

Identify ideal locations around Nottingham Trent University (NTU) such that the locations have access to a wide range of amenities, are safe and are in close proximity to the university (within a 5 km radius).

In this project, I utilise *[Foursquare API](https://foursquare.com)* to explore neighbourhoods around NTU to provide consultation for the best locations for investing in student accommodation. The solution provided will be useful for business owners to choose locations around NTU to provide accommodation services to university students. Mainly, the availability of facilities around the locations and the number of criminal events reported are taken into account. Usually, students prefer to live in close proximity to university campuses so the locations are restricted within a 5 km radius of NTU.


### Background

Nottingham is a city in central England’s Midlands region in the United Kingdom. There are around 65,000 students at Nottingham’s two universities — the University of Nottingham and Nottingham Trent University. With a huge student population, Nottingham is one of the most vibrant cities in the UK. Nottingham is ranked as the 6th best city in the UK for students and 48th in the world, according to the [QS Best Student Cities 2019](https://www.topuniversities.com/city-rankings/2019). Due to a large influx of students at the beginning of each academic year, university halls of residence are not enough to accommodate all the students. Also, most students prefer to seek residence via private student accommodation due to affordable rent and wider options in terms of location and housemates. This opens up the business opportunities to invest and explore private accommodation services to the university students ensuring maximum safety, accessibility to amenities and minimising distance to the University.


> You can read the complete report of the project as a medium article [here](https://medium.com/@nikesh.strat/identification-of-ideal-locations-for-student-accommodation-db13a0dca5dc) with the jupyter notebook [here](https://nbviewer.jupyter.org/github/LamaNIkesh/Coursera_Capstone/blob/87a56fb0b9ca29576d4a1d32bb9a6148d8e45269/Capstone_Uni_accommodation_final.ipynb)





