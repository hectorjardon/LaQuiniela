# LaQuiniela
The ultimate aim of this project will be to train an agent to learng how to bet in the Quniela betting system for La Liga. 

Currently you can find an SQL database with historic data of La Liga since 1995, constructed using Kishan Kumar's Kaggle dataset https://www.kaggle.com/datasets/kishan305/la-liga-results-19952020. In the database laliga.db you can find four tables: games, seasons, teams, standings. Games is the original Kaggle dataset after preprocessing. Seasons and Teams contains information on the available seasons and teams on the database. The standings table contains extensive week by week information on each team in the league. You can find the Jupyter notebook used to construct the database in the repository.

Next goal: use the laliga database to predict match outcomes!
