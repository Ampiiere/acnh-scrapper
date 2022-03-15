# Mini-Web Scrapper - Scrapping Animal Crossing Portal for villager popularity list.

### Introduction:
For this web scrapping project, we are going to be scrapping https://www.animalcrossingportal.com/, a fan made animal crossing community website. Specifically, The [Animal Crossing New horizons villager popularity list page.](https://www.animalcrossingportal.com/games/new-horizons/guides/villager-popularity-list.php#/)

The goal of this project is to obtain a full list of the villager's popularity ranking in anch. 
The page contains 6 tiers, classifying villagers into rankings of most popular to least popular, as we go down the page. Within each tier, Vilagers are ranked from most popular to least popular within their own tier. 

- The "Highest Popularity" tier contains 15 villagers
- The "Very Popular" tier contains 25 villagers
- The "Fairly Popular" tier contains 30 villagers
- The "Middle Ground" tier contains 60 villagers
- The "Less Popular" tier contains 120 villagers
- The "Least Popular" tier contains 163 villagers

We will attempt to scrap the tier of each villager, as well as their ranking in each tier from the website. 
For this project, we will be using Python, Beautiful Soup, pathlib, and Selenium webdriver. 

### Brief Description
From this project, I hope to obtain information about the popularity of each of the villagers. I will be combining the popularity data with another villager characteristic dataset , to see if there are any characteristics that correspond to higher villager popularity. 
