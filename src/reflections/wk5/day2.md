# Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
1. What are the three types of relationships?

1 to 1
1 to many
many to many

2. What are the benefits of the traditional linking of relationships instead of Embedding

Embedding is nice because it is more effecient to retrieve information. Traditional linking is more practical when you have multpile relationships accross your data set.


3. What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it?

How the data going to be accessed and used. For example on a popular page if the comments are left open and generate large amounts of responses the database can grow quickly. In this case we wouldn't want the comments directly load when the page loads. This could greatly affect a pages load speed and user experience.  