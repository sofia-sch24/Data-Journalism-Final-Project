# Data Journalism Final Project
## By Sofia Schnurer

dataset: https://datawrapper.dwcdn.net/TC3p9/1/ , https://www.kaggle.com/datasets/himanshunakrani/most-popular-on-netflix

## **Summary of Work**

This is a project meant to assess movies and tv shows on Netflix's top 10 list. This public data was created through Kaggle and taken directly from Netflix's Top 10 list. Popular movies are based of the amount of hours watched by viewers in the first 28 days. What is important about this dataset is how we can compare genres of popular movies and tv shows on the streaming site. We also have the ability to mark the differences and similarities between popular english and non-english films/tv shows. This dataset can give us a glimpse into current pop culture and the trends that drive the popularity of certain movies and tv shows. 

**Data Entry**

genre column added from IMDB
![data google sheets](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/5c1a19506c30ef1c8a3dfc149be32733d1536d7b/data%20netflix.png)

## Questions and Process
1. **Which genre is the most popular among English films and which genre is most popular among Non-English films?**

Genres among english films:
![english films genre](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/5539ad8aa98a4f0722b3999819bf21a16abc4c22/fav%20genre%20among%20english%20movies.png)

Genres among non-english films: 
![non english films genre](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/edd2ab95dc22d2c34f48da5509d1a9f6053ee609/fav%20genre%20among%20non-english%20movies.png)

Because this isn't a very long list, we can count which genres of movies are the most popular. For English films, it seems that drama movies are most popular. For Non-English films, it seems that thrillers are most popular. This isn't much of a difference in terms of popular genres because drama films contain similar cinematic elements to thrillers. 


2. **Which genre is most often in the top 10 list?**

![how many genre](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/64d755731f1fb03ff4f14231d1a8ffe06f64f155/how%20many%20genre.png)
Creating a pivot table helps us assess overall which films usually make the top 10 list, regardless of language. Overall, the genre that continues to make the top 10 list is **drama**. 

How I got to this answer: 
Went to insert and added "create pivot table" into a new sheet. For columns, I put "genre" and for values, I put "count of rank". 

3. **Which genre was less popular on the top 10 list?**

![less popular genre](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/1045fd88b4427cbe6b20e14baf78b36161ae9789/less%20popular%20genre.png)

To get this answer, I created a pivot table of different genres of movies and split them up amongst english and non-english films to compare. Overall, I decided that the least popular drama were romances because there was only one top ten film that was a romance in the non-english category. There were other columns with just one film such as comedy, crime, and mystery but these have a connect to other film genres such as "action_comedy" and "thriller". Romance movies on their own are a completely different genre that contains very different elements. 

How I found this: 
Went to insert and added "create a pivot table" in a new sheet. For columns, I put "language", for rows, I put "genre", and for values, I put "counta show_title"


4. **Which movie or tv show overall was most popular based on amount of hours viewed in the first 28 days and the rank of the show?**


![popular movie/show](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/8fea875a51cf6f5a7c07d0eca2553135bebb3577/most%20popular%20movie:tv%20show.png)

To find this, I had to create a filter of films and TV shows with the #1 rank. This should give me 4 columns. Then I assessed which ones had the most amount of hours. In conclusion, comparing both english and non-english shows/movies, the TV show Squid Game racked up the most amount of hours viewed within the first 24 days. 

How I got this answer: add filter, then used the formula in H2 which is =FILTER(A2:G41, C2:C41 = "1")


5. **How many hours of the Stranger Things was viewed globally in the first 28 days?**


![stranger things](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/1170c86030592872232ecae3cde28c478d2c1a7a/stranger%20things%20hours.png)

To find this, I created a filter of TV shows containing the term Stranger Things. Then I added the amount of hours from column M, and got an answer of **1893100000 hours**. 

How I got this answer: add filter and used the formula in H2 which is =FILTER(A2:G41, D2:D41 = "Stranger Things")


## Story Pitch and Sources

What intrigues me when it comes to this dataset is how I am able to compare trends among genre popularity and differences among shows/movies viewed in English and Non-English languages. I would like to interview both English and Non-English audiences to see if there are cultural differences that guide genre viewing. I'm curious to see whether the people I interview watch the TV shows and movies that are currently in the top 10 list on Netflix. I hope to compare these responses between English and Non-English speaking audiences. I would also try to gather a wide array of people to conduct interviews/surveys based on age, gender, and ethnicity. 

I chose these questions because they give an overall glimpse into popular movies and genres among English and Non-English languages. The findings from Stranger Things did surprise me a bit because I actually believed that Squid Game was the most watched show and not Stranger Things. 

My sources for this story pitch would include: 
Samana G, a recent college graduate (925) 848-4941
Mitzy W, a mom who works in auditing (310) 906-7323
Bob W, a retired French Hornist for the LA Philharmonic (323) 295-1843

These sources would provide me with a wide udnerstanding of interests and give me overall analysis into trending movies and TV shows among different age groups, genders, and ethnicities. I hope to find out whether Netflix's metrics for deciding what makes a show popular (hours viewed in the first 28 days) is actually an accurate assessment. This story would combine the data I've found in this project with the interviews I conduct. 
## Data Visualization 

https://datawrapper.dwcdn.net/TC3p9/1/
![scatter plot](https://github.com/sofia-sch24/Data-Journalism-Final-Project/blob/64f3eae4983ef99226f6f2f992a7c95fda1cc782/data%20visualization%20final%20project.png)

