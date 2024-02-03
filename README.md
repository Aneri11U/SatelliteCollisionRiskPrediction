# SatelliteCollisionRiskPrediction
This project shows the application of machine learning in space. We build the model to predict the final collision risk estimate between a given satellite and a space object (e.g. another satellite, space debris, etc).

PROBLEM DEFINITION:
Nowadays, active collision avoidance is a crucial task in space operations. Satellites in Low Earth Orbit receive numerous alerts regarding close encounters with other space objects, with hundreds of such alerts being issued every week. These alerts, which come in the form of conjunction data messages, need to be analysed thoroughly, and after careful evaluation, only about two actionable alerts per spacecraft and week remain. Hence, the development of fully automated techniques for predicting the collision risk can significantly reduce the number of false positives, making the process of avoiding collisions less expensive.

In this model we predicted the final collision risk estimate between a given satellite and a space object (e.g. another satellite, space debris, etc). To do so, we have used the  real-world data set prepared at ESA. In simple words, we have processed this huge data set and then predicted the risk using various regression methods. The method which showed the most accuracy was RandomForestRegression.

Dataset: https://www.kaggle.com/datasets/shadmanrohan/collisionavoidancechallenge

PACKAGES used:
- sklearn
- seaborn
- matplotlib
- pandas
