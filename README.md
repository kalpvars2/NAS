# NAS
This is a web-based news reader application which focuses on providing summarized news to the readers. Based on the user's past activity, the in-built recommender system provides the list of news. Also, another recommender system produces links to the news articles related to the one that the user just visited. The novelty of this software lies in its ability to deliver the news as an audio proving its usefulness for the visually-impaired people.
The backend of the application is built using the Django framework wherein the news articles are fetched using Google News API which will be rendered and displayed in a summarized format to the user. The data is being managed using SQLite which is the default database used in Django. The user details and the saved articles are stored in the database. 
The user may select the Read More option on the summarized news to get its complete news. Also, links to the articles related to that particular news will be put forward as suggestions. The sources of those articles will also be provided to authenticate that news. This will be implemented using the Web Scraping techniques in Python and Selenium.
Besides the aforementioned recommender, the application makes use of Machine Learning models to recommend the news articles from the genres frequently visited by the user. 
The voice browsing is triggered by saying ‘Read News’ and then it starts reading the news headlines as well as its summary. The user can say ‘Read More’ to listen to the complete news or ‘Next’ to jump to the next news headline.
The front-end of the application is built using ReactJs and has a convenient user interface. Users can register, login and logout in the application. After the user logs into the application, various headlines with a precise summary are displayed. The application also provides features like sharing articles on various social media platforms, commenting on a particular article and saving articles. Users can also upvote a comment and that will be displayed such that the comment with the highest number of upvotes is displayed on top.
