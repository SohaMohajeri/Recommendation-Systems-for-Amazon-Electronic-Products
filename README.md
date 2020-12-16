
<div align="center">
  
# Recommendation Systems for Amazon Electronic Products
</div>


<div align="center">
<img src="https://user-images.githubusercontent.com/69224996/96965816-a9815080-14c1-11eb-8dfe-49afac54d17d.png" >
</div>

<br />

<div align="justify">

Online E-commerce websites like Amazon, Filpkart uses different recommendation models to provide different suggestions to different users. Amazon currently uses item-to-item collaborative filtering, which scales to massive data sets and produces high-quality recommendations in real time. This type of filtering matches each of the user's purchased and rated items to similar items, then combines those similar items into a recommendation list for the user. In this project we are going to build recommendation model for the electronics products of Amazon.

The main types of recommendations systems include:

**Popularity-Based Recommender**
- It offers generalized recommendations to every user, based on product popularity. This system recommends same products to all users and it does not give personalized recommendations to users.

**Content-Based Recommender**
- It builds an engine that computes similarity between products based on certain metrics such as description, and suggests products that are most similar to a particular product that a user liked. The general idea behind these recommender systems is that if a person liked a particular item, he or she will also like an item that is similar to it.
Collaborative Recommender
This system matches persons with similar interests and provides recommendations based on this matching. Collaborative filtering is based on the idea that users similar to a particular user can be used to predict how much that particular user will like a particular product or service those users have used/experienced but that particular user has not.

**Hybrid Recommender**
- This system builds an ensemble of Collaborative, Content-Based or Popularity-Based models to come up with a comprehensive Hybrid Recommendation System.


Amazon Reviews data source has several datasets. For this case study, we are using the Electronics dataset (https://www.kaggle.com/saurav9786/amazon-product-reviews) which includes:
- userId : Every user identified with a unique id
- productId : Every product identified with a unique id
- Rating : Rating of the corresponding product by the corresponding user
- timestamp : Time of the rating ( ignore this column for this exercise) 


Our objective is to build a recommendation system to recommend products to customers based on the their previous ratings for other products. For this purpose, first we will perform exploratory data analysis and then implement three recommendation algorithms including Popularity-Based, Collaborative, and Hybrid Recommenders.

</div>

