# Natural Disasters (2000-2021) using Data Visualization

The disaster is the impact of both natural and man-made events that influence our life and environment that surrounds us. Now as a general concept in academic circles, the disaster is a consequence of vulnerability and risk. The time often demands for appropriate reaction to face vulnerability and risk. The vulnerability is more in densely populated areas where if, a bad event strikes leads to greater damage, loss of life and is called as disaster. In other sparely populated area the bad event may only be a risk or hazard.

Developing countries suffer the greatest costs when a disaster hits – more than 95 percent of all deaths caused by disasters occur in developing countries, and losses due to natural disasters are 20 times greater as a percentage of GDP in developing countries than in industrialized countries. A disaster can leads to financial, environmental, or human losses. The resulting loss depends on the capacity of the population to support or resist the disaster. The term natural has consequently been disputed because the events simply are not hazards or disasters without human involvement.


## Types of Disasters :

1) Geological Disasters : 
	Avalanches and landslides,
 	Earthquakes,
 	Sinkholes,
 	Volcanic eruptions,
	Duststorms
  
2) Hydrological Disasters :
	 Floods,
	 Tsunami,
	 Limnic eruptions
   
3) Meteorological Disasters :
	 Tropical cyclone,
	 Blizzards,
	 Hailstorms,
	 Ice storms,
	 Cold waves,
	 Heat waves,
	 Droughts,
	 Thunderstorms,
	 Tornadoes,
	 Firestorms
   
4) Wildfires

5) Space Disasters :
	 Impact events and airburst,
	 Solar flare

## About Dataset :

* Used a CSV dataset of Natural Disaster(2000-2021).There are 19 columns and 8949 rows in the dataset.

* The columns are Year, Disaster Subgroup, Disaster Type, Disaster Subtype, Country,ISO,Region,Location,Start Year,Start month, Start Day,End Year, End Month,End day,Total Deaths,No Injured,No homeless,Total Affected and Total Damages.

* The first attribute Year has the values from 2000 to 2021 and there is no null values in this attribute(Integer datatype).

* The disaster subgroup consists the data that clearly tells about the disaster subgroup like whether it is hydrological,meteorological,biological etc and zero null values.(String datatype) 

*	The disaster type attribute has the data like landslide,Epidemic,floods,storms etc and no null values in the column.(String datatype).

*	The disaster subtype attribute has the data that describes the disaster type like Bacterial disease (Epidemic),Convective storm(storm),Riverine flood(Flood) etc and there are 1292 null values in the column.(String datatype)

*	Country attribute shows the list of countries where disasters happened and it has no null values(String datatype).

*	ISO attribute has the data that shows the standard short form of the country name and it has zero null values(string datatype).

*	Region attribute has the specific region where the disaster occurred with zero null values(string datatype).

*	Location column gives the information about the location the region where the disaster occurred and it has 249 null values(string datatype).

*	Start year attribute it shows the year  when the disaster started and it has 15 null values in the column(integer datatype).

*	Start month column shows the month when the disaster started and there are 63 null values(integer datatype).

*	Start date column has the date when the disaster started and there are 1350 null values(integer datatype).

*	End year attribute consists  information of  the year when the disaster end by and it has 2 null values(integer attribute).

*	End month column gives the information of the month when the disaster end by and it has 157 null values(integer datatype).

*	End date column gives the data about the date when the disaster ended and it  has 1309 null values(integer datatype).

*	Total deaths column consists of total number of deaths occurred at the time of disaster happened and it has 2579 null values(integer datatype).

*	No injured attribute gives the count of  people who injured at the time of  disaster and it has 6563 null values(integer datatype).

*	No homeless column gives the count of  homeless people due to disaster and it has 7784 null values(integer datatype).

*	Total affected attribute gives the information about total number of people affected by disaster in many ways and it has 1778 null values(integer datatype).

*	Total damages column consists of  number of  people whose properties were damaged by the disaster and it has 6130 null values(integer datatype).

## PLOTS and GRAPHS used for Visualization :

1.	Heat map : It shows the Null values in Dataset.

2.	Swarm plot : Plotting total Disasters per country in 2021.

3.	Count plot

     a)	Plotting Count of Disaster Type and Subgroup’s where Year Ranging from 2000 — 2021.
     
     b) Plotting Disaster Subgroup and Total Affected in India.
     
4.	Strip plot : Plotting Top 10 Highest Total Affected Count with respect to Countries.

5.	Pair plot : Pair Plot of all the possible pairs from CSV.

6.	Rel plot : Plotting Total Affected Per Year.

7.	LM plot : Plot of Total Homelessness among the Total Affected of every Year represented by years.

8.	Violin plot : Plotting Homeless of each Year.

9.	Word Cloud : Display the types of Natural Disasters.

10.	 Waffle Chart : For plotting Disaster type.

11.	 Joint Plot : Plotting Disaster type and Disaster Subgroup.

12.	 Dis Plot : Plotting number of regions.

13.	 Scatter Plot : Visualizing Total damages occurred in particular year.



## Python Libraries used : 

•	Matplotlib: Cross platform for DV and graphical plotting library in python.
Matplotlib supports all the popular charts (lots, histograms, power spectra, bar charts, error charts, scatterplots, etc.) right out of the box. There are also extensions that you can use to create advanced visualizations like 3-Dimensional plots, etc.


•	Pandas: Famous and highly used data manipulation tool and its key data structure is df which is used to store and manipulate tabular data in rows of observations and columns of variables.


•	Seaborn: Core purpose is making statistical graphics in python and can be customized easily, useful feature of Seaborn is that it supports a plethora of advanced plots like categorical plotting (catplot), distribution plotting using kde (distplot), swarm plot, etc. right out of the box. And of course, we saw one example of relplot above.


•	WordCount: Wordcount library and stopwords is used to eliminate words that are commonly used which carries very little useful info.


## Conclusion : 

Good data visualization communicates a data set clearly and effectively by using graphics. The best visualizations make it easy to comprehend data at a glance. They take complex information and break it down in a way that makes it simple for the target audience to understand and on which to base their decisions. Conclusions like frequently occurred natural disaster (Floods) , year which had high count of homeless (2006), country which faced maximum number of total affected cases (China) are inferred from graphs. 

These visualizations can help in taking measures to prevent the loss which occurs. Good governance of disaster risk is essential for making communities resilient to natural phenomena. There is an urgent need to invest in disaster risk reduction to minimize our vulnerability to future events. To date, much of the focus has been on reactive measures to address sudden onset events such as storms and landslides, including humanitarian aid relief and preparedness. However, climate change is also responsible for slow onset disasters such as drought. While emergency measures are critical in times of disasters and require continued efforts, as a global community we must move from reactive to proactive risk reduction. Proactive investments in risk reduction can help countries prepare for this type of disaster that may be ‘invisible’ until a crisis point is reached, when more resources may be required to reverse the damage. 


## References :

1. https://matplotlib.org/
2. https://towardsdatascience.com/seaborn
3. https://seaborn.pydata.org/
4. https://pandas.pydata.org/
5. https://www.kaggle.com/brsdincer/all-natural-disasters-19002021-eosdis
