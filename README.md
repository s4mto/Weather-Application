## Weather APP

# What is this project?

- In this project, a weather application including city, population and region data in the ***Netherlands***, ***Turkey*** and ***USA*** was made for users.
- The purpose of this project was to provide users with access to the weather information of your location or the city you want in the ***Netherlands***, ***Turkey*** and ***USA***.
- n addition, it was to show the region and population data of cities in the ***Netherlands***, ***Turkey*** and ***USA***.

# How was this project done and what tools were used?

- We completed this project with my other ***3 teammates*** in a period of ***10 days***.
- We applied ***Agile Scrum methodology*** during the project process. In this way, we were able to control our progress and also exchanged ideas.
- In the project, we reached the data of the countries by ***Web Scraping*** on ***Wikipedia***, and we reached the weather data using the ***API*** on the ***freeweather site***.
- We collected our codes with ***branches*** we created on ***Github*** in our repostory on github.
- We used ***PyQt5 Designer, Python, Trello, VsCode*** and ***GitHub*** in the project.

# My roles in the project:
- Preparing the database and pulling the data over ***PostgreSQL***,
- Preparing the region and population data of cities in the ***Netherlands***, ***Turkey*** and ***USA*** by ***Web scraping on Wikipedia***

# Results;
* I reinforced using ***Web Scraping*** and ***API*** in the project,
* It helped me develop myself in ***working as a team***.



## Steps


* Step 1:
* Design GUI for Weather App
* Consider Web Scrapping Data Visualisation
* Consider Web API Data Visualisation
* UML Design (Making Plan)


* Step 2:
* Scrapy will be used extracting the data you need from Wikipedia web site.  
https://nl.wikipedia.org/wiki/Lijst_van_Nederlandse_plaatsen_met_stadsrechten
https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population https://tr.wikipedia.org/wiki/T%C3%BCrkiye%27deki_illerin_n%C3%BCfuslar%C4%B1_(2020)  
* City, state and population information is drawn from the website addresses with Scrapy.
* The name of the selected City will be displayed in the program.
* The region or state of the selected City will be shown in the program.
* The population of the selected City will be displayed in the program.
* All information should be ordered and stored in DB   


* Step 3:

* HTTP-Request and API will be used to pull real-time weather information from the website.
* Weather information of the selected cities is taken from https://openweathermap.org/api site.(You can choose other web sites)
* The Temperature of the selected City will be displayed in the Program.
* The Weather of the selected City will be displayed in the program with Icons.
* The icons and how to use the icons are explained in detail on the site given below,
https://openweathermap.org/weather-conditions .
* All information should be ordered and stored in DB

* Step 4:
* Program Main page will contain the following components.
* Countries
* Selected Country, Cities, Regions, Populations ordered By Population
* City Search Bar
* Selected City Name,
* Selected City Region,
* Selected City Population
* Selected City Temperature (Celsius)
* Selected City Weather Condition Icon  


* Step 5:
* Final presentation 

* GitHub Usage Requirements
* Each team will have a GitHub repository and each team member will be added as a collaborator. 
* All tasks should be created as an issue on the issues page.  
* Each team member will get assigned issues.  
* Master will be protected. Branches and pull requests will be used for development.
