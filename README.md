# Building a recommendation system for movies.

Even though peoples’ tastes may vary, they generally follow patterns. There are similarities in the things that people tend to like … 
or another way to look at it, people tend to like things in the same category or things that share the same characteristics.
For example, if you’ve recently purchased a book on Machine Learning in Python and you’ve enjoyed reading it, 
it’s very likely that you’ll also enjoy reading a book on Data Visualization. 
People also tend to have similar tastes to those of the people they’re close to in their lives. 

Recommender systems try to capture these patterns and similar behaviors, to help predict what else you might like. 

Recommender systems have many applications that I’m sure you’re already familiar with. Indeed, Recommender systems are usually at play on many websites.
For example, **suggesting books on Amazon** and **movies on Netflix**. If a certain movie gets viewed frequently enough, Netflix’s recommender system ensures that that movie gets an increasing number of recommendations. 
<u>**Another example**</u> can be found in a **daily-use mobile app**. On social media, sites like **Facebook** or **LinkedIn**, regularly recommend **friendships**.

## the main benefits of using a recommendation system. 
One of the main advantages of using recommendation systems is that **users get a broader exposure to many different products they might be interested in**. 
This exposure encourages users towards continual usage or purchase of their product. 
Not only does this provide a better experience for the user but it benefits the service provider, as well, 
with increased potential revenue and better security for its customers. 

## There are generally 2 main types of recommendation systems: 
    Content-based and collaborative filtering. 
The main difference between each, can be summed up by **the statement that a consumer might make**. 
For instance, the main paradigm of a **Content-based recommendation system** is driven by the statement:

     **Show me more of the same of what I've liked before.**

Content-based systems try to figure out what a user's favorite aspects of an item are, and then make recommendations on items that share those aspects.
**Collaborative filtering** is based on a user saying, 
         
     **“Tell me what's popular among my neighbors because I might like it too.”**
Collaborative filtering techniques find similar groups of users, and provide recommendations based on similar tastes within that group. 
In short, it assumes that a user might be interested in what similar users are interested in. 

![Intro-to-Recommender-Systems-Coursera1](https://user-images.githubusercontent.com/84151016/129804601-55f06fca-648a-4277-9b9c-c4ce8a5692b9.png)

Also, there are **Hybrid recommender systems**, which combine various mechanisms. 
In terms of implementing recommender systems, there are 2 types: **Memory-based and Model-based**. 
   **In memory-based approaches.**
   we use the entire user-item dataset to generate a recommendation system. It uses statistical techniques to approximate users or items. 
   Examples of these techniques include: Pearson Correlation, Cosine Similarity and Euclidean Distance, among others. 
   
   **In model-based approaches.** 
   a model of users is developed in an attempt to learn their preferences. Models can be created using Machine Learning techniques like regression, clustering, classification, and so on.

