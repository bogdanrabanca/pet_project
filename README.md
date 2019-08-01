# pet_project
This project analyzes data about the dog population of New York City.
I gathered pet data as well as neighborhood maps and population from [NYC Open Data](https://opendata.cityofnewyork.us/), and I scraped some additional data on dog weights and breed images. After cleaning up the data and organizing it, I look into four main questions:

(1) what are the most popular names? (in NYC, by borough, by year)

(2) what are the most popular breeeds? (same as above)

(3) what is the distribution of dog weights across the city? more specifically, are there particualr neighbohoods where dogs are relatively heavier?

(4) what is the ratio of dogs to human population per neighborhood?

This project also has a (slightly different) [Tableau version](https://public.tableau.com/profile/bogdan.rabanca#!/vizhome/dogsofnewyork3/Story1).

Packages you'll need to install: 

[pandas](https://pandas.pydata.org/)

[bokeh](https://bokeh.pydata.org/en/latest/)

Note: Initially I downloaded the dog license data programatically from NYC Open Data. Unfortunately, the city updated the file with a new file containing less information (most importantly, the new file lacks neighborhood data) and using that file will make some visualizations unavailable. So now I am just using the older version of the file in .csv format.
