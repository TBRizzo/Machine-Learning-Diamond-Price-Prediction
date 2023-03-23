<h1 align="center"><img src="https://bit.ly/2VnXWr2" width="60">

<h1 align="center">Machine Learning: Diamond Price Prediction with Linear Regression </h1>

<p align="center"> Fourth project developed in the Ironhack Data Analysis Bootcamp </h1>

![image](https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white)
![image](https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![image](https://img.shields.io/badge/NumPy-013243.svg?style=for-the-badge&logo=NumPy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![image]([https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white](https://seaborn.pydata.org/_images/logo-wide-lightbg.svg))
![image](https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)

##  💻 About the project</br>

The main goal of this project was obtaining data from some source of our choice and safely storing it in a database. After that, it was also required that we presented a business presentation using info from the dataset we obtained from the data gathering step.

In my work I gathered data using API and webscrapping (although I ended up using only the information obtained through webscrapping, as it was more complete) from the website "Raider.io", a website that registers all dungeon runs in World of Warcraft, to help a player that has as a goal to become a streamer playing World of Warcraft and would like to know with which class to start playing, considering that his channel will have more visibility if it streams content within the competitive scene, i.e. a class that has a greater chance of being competitive in the next season, based on the history of previous seasons.

## 🛠 Data Gathering:

As mentioned before, the data was obtained through webscrapping from the raider.io page, from all main seasons that have already ended, creating a csv file with "role" (tank, healer or dps), "season", "class" and "region".
In this repositorie, you can also find the raider.io's public API notebook. The problem with the public API is that the number of pages from which data can be extracted is 100, which greatly limited the amount of data and was therefore not considered.

## 🛠 Data Visualization:

The visualization part was made on Tableau and can be found on the following link: https://public.tableau.com/app/profile/thomaz.rizzo/viz/projectAPI-WoW/Histria

##  💻 Result Analysis:

By looking at the Tableau dashboards, we could visualize the data and come to the following conclusions:

1) Region: There were no relevant differences from region to region. in all regions the players were playing with the same classes, which was to be expected, since the same game, with the same metrics, is played in all regions.. 
2) Classes: The safe choices chosen for each class were chosen based on how often on past season did they appear as "picked by at least 20% of the players".
2.1: Tanks: Death Knight > Warrior;
2.2: Healers: Druid > Paladin > Shaman = Priest
2.3: DPS: Hunter > Rogue = Mage

## 🛠 Data Sources:

Raider.io Public API: https://raider.io/api#/mythic_plus/getApiV1MythicplusRuns
Raider.io: https://raider.io/mythic-plus-rankings/season-sl-4/all/us/leaderboards-strict
