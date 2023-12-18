# Machine Learning Path


## Description
**Learnfonify**: our app will recommend programs like online courses, webinars, and events in one place that will greatly help students improve their skills or gain new knowledge so they can become competent in their areas of interest. The app will also recommend programs based on what users like.


## Recomendation System
**Collaborative filtering** is a technique that can filter out items that a user might like on the basis of reactions by similar users. It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user.

**User-based**: For a user U, with a set of similar users determined based on rating vectors consisting of given item ratings, the rating for an item I, which hasn’t been rated, is found by picking out N users from the similarity list who have rated the item I and calculating the rating based on these N ratings.


## Dataset 
We collect program data, such as online courses, webinars, and events, from third-party applications/websites that match our projects. We process the data ourselves to generate datasets that can be used for recommendation models. For the datasets you can see [here](https://docs.google.com/spreadsheets/d/1QbMJq1l0bIxbWolGIwkln2lBhMNqAF1RCxuKuXTo6n0/edit?usp=sharing).


## Reference
*  Collaborative Filtering in [here](https://heartbeat.comet.ml/build-train-and-deploy-a-book-recommender-system-using-keras-tensorflow-js-b96944b936a7) and [here](https://medium.com/@kunalmahadik27/collaborative-filtering-for-recommender-systems-34b9135ce07b)
