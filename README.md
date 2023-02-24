# NBAPositionClassifier-

This project was based upon the classification problem of Can the positions of NBA players be correctly classified based on regular season statistics?

Some in-game stats such as Points per game (PPG), assists, blocks, rebounds and field goal percentage (FG%) were chosen to be attributes of each data point.
The top 33 players by PPG for each position for the 2021 NBA season were chosen as data points, the three positions chosen were guard,forward, and center. 
The following subplots demonstrate the seperation between each class for each attribute.
<img width="810" alt="image" src="https://user-images.githubusercontent.com/102476062/221088476-982401fe-37bc-45df-808c-0161b97b24ff.png">

By using the sklearn framework it was possible to create both a training and test data set, the standardscaler was chosen as it was shown have a higher Knn score
(fractional score of the instances that are correctly predicted). The model accuracy is shown below

<img width="243" alt="image" src="https://user-images.githubusercontent.com/102476062/221088665-906474ab-2421-4bbd-9b9d-619090858e7d.png">
<img width="243" alt="image" src="https://user-images.githubusercontent.com/102476062/221089283-2ea519b1-e221-4119-beeb-0d173f87a546.png">

A confusion matrix was set up to determine the amount of true positives, false positives, true negatives, and false negatives. The confusion matrix showed that
the classification of guards and centers were reliable, however the classification of forwards was not. 

<img width="307" alt="image" src="https://user-images.githubusercontent.com/102476062/221088869-5671057e-05bc-48e3-a76f-858fb4d9ea18.png">

The model was then tested by inputting the data of an NBA forward Michael Porter Jr. The model was able to accurately predict his position as a forward. 
<img width="402" alt="image" src="https://user-images.githubusercontent.com/102476062/221089010-1a7ae505-cfc4-46e9-ad21-1c8b3e618816.png">



Credits: Lionel Hasan, Eric Mei, Liam Mah, and Theodore Hoang 
