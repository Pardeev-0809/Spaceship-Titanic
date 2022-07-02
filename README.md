## Kaggle Spaceship Titanic Machine Learning Project 
This repository contains Spaceship Titanic machine learning project with jupyter notebook files. There are 3 .csv files 'train.csv', 'test.csv' and 'sample_submission.csv'.

* Data in train.csv -> PassengerId, HomePlanet, CryoSleep, Cabin, Destination, Age, VIP, RoomService, FoodCourt, ShoppingMall, Spa, VRDeck, Name, Transported

* Data in test.csv -> Same as train.csv excluding Transported field

* Data in sample_submission.csv -> PassengerId, Transported (It is the sample file showing how the data should be submitted to Kaggle)

---

During the Competition our Position on the Leaderboard:
1. Rank: 2201 | Accuracy: 52.00%
	* We use KNN algorithm and replacing NULL values with previous data's values
1. Rank: 1441 | Accuracy: 78.70%
	* We use Random Forest algorithm and replacing NULL values with evenly distributed values in the dataset
1. Rank: 2201 | Accuracy: 52%
	* We use Random Forest algorithm and replacing continuous NULL values with Median and categorical NULL values with Mode


---

