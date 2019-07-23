# pet_project
This project analyzes data about the dog population of New York City.
I gathered pet data as well as neighborhood data from [NYC Open Data](https://opendata.cityofnewyork.us/), and I scraped some additional data on dog weights and neighborhood populations. I look into what are the most common names and breeds in NYC as a whole and in specific boroughs.

Eventually I will include an interactive tool where users can drill down for data at neighborhood level. I also plan to include map charts showing average dog weights and dog counts for each neighborhood. 

This project also has a [Tableau version](https://public.tableau.com/profile/bogdan.rabanca#!/vizhome/dogsofnewyork3/Story1).

Packages you'll need to install: 

[pandas](https://pandas.pydata.org/)

[bokeh](https://bokeh.pydata.org/en/latest/)

Note: Initially I downloaded the dog license data programtically from NYC Open Data. Unfortunately, the city updated the file with a new file containing less information (most importantly, the new file lacks neighborhood data) and using that file will make some visualizations unavailable. So now I am just using an older version of the file in .csv format.
