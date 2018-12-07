# Global-Terrorist-Attacks
Multi-Class Classification Problem 

__Data__: [GTD](https://www.start.umd.edu/gtd/) (Golbal Terrorism Database) is an open-source data base, containing information about over 180,000 terrorist attacks that were recorded from 1971 to 2017, including features such as date/time, location, attack type, responsible group (if identified), target type, weapon type, and fatalities/injuries.  

__Motivation & Goal__: Prediction of terrorist group after an attack is one of the
most important steps for counter terrorism. As soon as we are able to find the involved group name, we will be able to make strategies to catch the culprits. 
The goal of this project is to build a classifier that can classify the Perpetrator Groups based on the 135 features provided. 82782 among 181691 attacks have unknown terrorist groups. There are in total 3536 different identified terror groups, and they normally work individually, only 0.03241 collaborate with other groups ((df['gsubname'].notnull()).sum()/181691). 

__Models__: Classify those groups based on the country, location, targettype, weapon etc information. Classification models: Tree models, KNN, and Neutral Network. Tree models are insensive to the imbalanced dataset.    

__Evaluation Metrics__: Accuracy Score is the percentage number of
correctly classified instances (the number of correct
predictions from all predictions made).; F1-Score, the balance between precision and recall. 
