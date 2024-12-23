# Exploratory Data Analysis - GoodReads Dataset
#### I was able to generate insights from our exploratory data analysis and below are some of the important insights:<br><br>
1. I observed that there is a relationship between the average rating and rating count, as several ratings increase, the rating of books seems to move towards 4, and as the number decreases, the rating becomes sparse.<br>
2. I observed that readers prefer books with a moderate range of pages (around 200 – 400) as the highest number of ratings are given in that range.<br>
3. I also discovered that authors whose books are highly rated are Stephen King, P.G. Wodehouse, Rumiko Takahashi, Orson Scott Card, Agatha Christie, etc. because their work has been present for quite a while, spanning decades.<br>
4. I found that the most highly rated publishers are so due to having a limited number of highly satisfied readers.<br>
5. I also observed that the authors with the highest ratings have a smaller number of total reviews, a smaller number of books published in the years, and vice versa.<br>
6. The quantity of reader ratings has very little effect on the number of text reviews posted on the Goodreads website. Even if the number of reviews for a book is high, the ratings for that book may be poor.<br>

In this project, the goal was to predict the ratings of a book in the Goodreads dataset using a linear regression algorithm. The dataset was analyzed using Univariate Data Analysis and Principal Component Analysis (PCA) to gain insights and create 8 visualizations to understand the correlation among the variables. The ggplot2 library was used to create the visualizations.
Linear regression was implemented to predict the ratings of a book using the available features such as the number of pages, author, publisher, and year of publication. The model was trained on a portion of the dataset and tested on the remaining portion to evaluate its accuracy.
<br>
<br>
Univariate data analysis is a technique of analyzing a single variable to understand its behavior and characteristics. In the context of Goodreads EDA, univariate analysis can be used to study various variables related to books and user reviews, such as book ratings, number of ratings, publication year, author, genre, etc. It helps to understand the distribution and frequency of the variables and identify any outliers or missing values.
<br>
<br>
Principal Component Analysis (PCA) is a technique used to identify patterns and correlations among variables by reducing the dimensionality of the data. In the context of Goodreads EDA, PCA can be used to identify the most important variables that contribute to the overall variation in the dataset. It can help to identify any hidden trends and patterns among the variables and to determine the relationships between them.
<br>
<br>
Together, univariate data analysis and PCA can provide valuable insights into the Goodreads dataset, helping to understand the characteristics of the books and user reviews, and identifying any important variables that may affect the book ratings. This can help to inform marketing strategies and improve the overall user experience on the Goodreads platform.
<br>
<br>
The project helped in gaining insights into the factors affecting the ratings of books and creating a model to predict ratings using available features. The visualizations and analysis provided a better understanding of the dataset and helped in improving the accuracy of the prediction model.
