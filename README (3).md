
# Project 2 MIST 4610
Group Name: 21479_ 7

    Team Memebers and GitHub Links

Cole Wright, https://github.com/cole16wright

Ashley Parker, https://github.com/ashleyparker801 

Erica Degue, https://github.com/ericadegue

Iti Jain, https://github.com/iti-jain/

Isabella Escorcia, https://github.com/isa-escorcia

Dataset: https://www.kaggle.com/datasets/shivamb/netflix-shows 

    Our Dataset
This dataset contains a list of all the movies and TV shows listed on Netflix (as of 2 years ago). Our data was obtained through Kaggle.com. The data has 8807 unique instances and 12 attributes to describe each piece of cinema. The columns show whether it is a movie or TV show, the title, director, main cast, country of production, date added, release year, rating, duration, genre, and a basic description. It gives the information for each movie and show listed to provide a solid understanding of all the content within Netflix’s catalog at the time.  

    Question 1 and It's Relevance
The first question we asked was “which countries produce the most content?”.  Knowing which countries produce the most content is useful because it shows where Netflix is already successful in its targeting efforts and which countries have a more developed film industry. This gives them the necessary data to focus on marketing more/less in varying regions. Also, producing content in some countries can be cheaper, so by identifying countries that produce high-quality content at a lower cost, Netflix can allocate funding in a cost-optimization mindset. Furthermore, this data can tell us which countries are the most influential in regards to film and media culture. Netflix can use this data to generate more content in these countries and dive deeper into why so much is produced there based on factors like the size of the film industry, country regulations, etc. Knowing which countries produce the most content can give Netflix a competitive advantage because by analyzing the strengths and weaknesses of competitors in each country, Netflix can develop strategies to outperform them and gain market share to be the most successful streaming platform.

    Question 2 and It's Relevance
The second question we asked was “which genres are the most popular?”. Understanding which genres of content are most popular is essential for any media company because it helps them make informed decisions about where to invest resources. By analyzing viewing trends and consumer preferences, executives can identify which genres of content are in high demand and plan accordingly. For instance, if comedy films have been increasing in popularity, Netflix may want to invest in producing more comedy specials or TV shows. By doing this over multiple years, Netflix can track trends in genre popularity and predict which types of content will perform well in the future. Predicting the future popularity of specific genres is important as it can take a long period of time to develop a movie or show, therefore media companies need to be prepared to start production for a project in a certain genre to be ready for release when it would be most successful. Each country has its own unique culture, and understanding the types of content that are popular in different countries can help Netflix create more culturally relevant content. This can help Netflix attract more viewers and build a stronger brand identity in those countries. Ultimately, understanding which genres are most popular can help Netflix stay ahead of the curve and deliver content that resonates with its audience.

    Manipulations Applied to the Dataset 
For our dataset, we did have to do some manipulations in order to generate the results that we wanted. The biggest issue that we encountered was that the genre and country information was not separated in the dataset. The reason was that some movies or TV shows can be included in multiple genres or produced in different countries. To make this data usable for our project, we had to manually isolate the genre and country information for each entry.
To accomplish this, we made two separate Excel sheets from the original dataset. We went through the Netflix_titles.csv file and separated and accounted for each country listed by the movie or tv show. We put this into a separate Excel which had 3 columns: Country, Type (TV or Movie), and count. We then went through and took a count for each country and took separate counts for movies and another count for TV shows in that country. We went through and did the same thing for the genres and made a separate Excel for them as well.

    Analysis and Results
To answer our first question, we created a map in Tableau to visualize the number of TV shows and movies produced by each country. The map showed that the United States had the highest number of productions with 3,274 titles, followed by India with 1,007 titles. Other countries with a significant number of productions included the United Kingdom (708 titles), Canada (414 titles), and France (361 titles). This data makes sense because Netflix has a large percentage of subscribers from those countries. Furthermore, India and the United States are likely the largest because movies produced in Hollywood and Bollywood are enjoyed worldwide and have a history of commercial success. We decided to take our data a step further by picking one of the top content creating countries (France) and seeing whether they made more films or TV shows. We found that they made 285 movies and 76 TV shows. One reason French media may prefer to make movies instead of TV shows may be due to the worldwide popularity of French film festivals such as Cannes. 

To answer our second question, we created a bar chart differentiated between tv shows and movies to measure which genres were the most popular in each category. When we analyzed the data based on the genre of content produced and excluded the ‘International’ category as it isn’t a specific genre, we found that Drama was the most popular genre, followed by Comedy in both the tv show and movie category. However, in the third most popular slot, action was the most popular genre in movies and crime was the most popular genre in tv shows. This suggests that viewers prefer similar content regardless of the media format. We wanted to compare the genres of movies and TV shows in 2014 and 2019. There was not much data for 2014 but in 2019 the most popular genres were dramas and comedies (excluding International movies). This data aligns with our main graph for this question. Although information for 2014 is limited, it may suggest that these genres have grown in popularity more recently. Our group also looked at the genres of content in the United States vs India. The top two genres were dramas for both countries. The large difference in popularity between dramas and other genres suggests that content in this category will most likely see more success that others like horror.
 In 2022, Netflix spent approximately $16.8 billion on producing original content (statista). This data is important in determining the allocation of that budget. According to our analysis, the majority of that budget would likely go to drama and comedy content produced in the United States or India.


    Visualizations 
![alt text](https://github.com/cole16wright/SQL_PROJECT2/blob/main/top%205.png)


^ Countries Producing The Most Content

![alt text](https://github.com/cole16wright/SQL_PROJECT2/blob/main/franceGenre.png)


^ France TV Shows vs Movies

![alt text](https://github.com/cole16wright/SQL_PROJECT2/blob/main/topGenres.png)


^ Top Genres on Netflix by Uploads

![alt text](https://github.com/cole16wright/SQL_PROJECT2/blob/main/2014vs2019.png)


^ Types of Movies and TV Shows Released in 2014 vs 2019

![alt text](https://github.com/cole16wright/SQL_PROJECT2/blob/main/typesofMovie.png)


^ Types of Movies and TV Shows Released in United States vs India





