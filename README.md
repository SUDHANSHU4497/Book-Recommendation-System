# Book-Recommendation-System
1. Introduction
2. Problem Statement
3. Dataset Information
4. Conclusion

<p align="center">
  <img 
    width="750"
    height="400"
    src = "https://miro.medium.com/max/623/1*hQAQ8s0-mHefYH83uDanGA.gif">
</p>



*****

1. Introduction:

  The purpose of a recommendation system basically is to search for content that would be interesting to an individual. Moreover, it involves a number of factors to create personalised lists of useful and interesting content specific to each user/individual. Recommendation systems are Artificial Intelligence based algorithms that skim through all possible options and create a customized list of items that are interesting and relevant to an individual. 

2. Problem Statement

  The traditional book ordering system is a manual and time-consuming process wherethe customer has to visit a bookstore to search and purchase the books. In this tightschedule, problems arise in finding specific books due to the inadequate distribution of books through the bookshop. The buyer could not get a recommendation for the correctselection of books.

3. Data Information
    * Books – first are about books which contain all the information related to books like an author, title, publication year, etc.
    * Users – The second file contains registered user’s information like user id, location.
    * ratings –  Ratings contain information like which user has given how much rating to which book.
    
4. Conclusion:

    * 67.43% users give 0 rating for books and only 32.57 % user are positively rated the books.
    * 72% of books reader from USA and 9% from Canada
    * Stephan King is most popular author and rated by most of the users, Nora Roberts was second after Stephan king.
    * The lonely Bones: A Novel is most rated books followed by The Da Vinci Code.
    * Most of the user who rate the book are from adult age group and the age group who rate down are adult.
    * The Lovely Bones: A Novel written by Alice sebold is more popular among teen and it is rated by maximum number of users.
    * Harry Potter and the Chamber of Secrets (Book 2) is getting maximum weighted score.
    * For modelling, it was observed that for model based collaborative filtering SVD technique worked way better than NMF with lower Mean Absolute Error (MAE) .
    * In cases where a new user or item's rating preference is unknown, collaborative filtering may not be the best recommendation approach. Content-based screening is preferable.
