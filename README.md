# nosql-challenge
I have loaded json data into a Mongo database and used PyMongo to query and perform analysis on the data in Jupyter Notebook. After importing the data and creating an instance of Mongo Client, I updated the database with a new document. I then transformed the data by removing unwanted documents and changed the data types on some of the number values. Finally, I performed analysis to answer the following questions: 

Which establishments have a hygiene score equal to 20?

Which establishments in London have a RatingValue greater than or equal to 4?

What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added, "Penang Flavours"?

How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
