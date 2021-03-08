3/2/2021
Read Servers with Node/Express > MongoDb Relationships and answer the following questions
What are the three types of relationships?
One to One, One to Many, and Many to Many.

What are the benefits of the traditional linking of relationships instead of Embedding?
A benefit is that extra comments will not increase the original document, making it less likely that the applications will run in the maximum document size. It's also much easier to return numbered comments.

What are some of the challenges faced when deciding how to manage a many-to-many relationship that ultimately drive your decision on how to create it? 
You have to think about how your data interacts with each other. You can then decide if you want to use One Way Embedding, Two Way Embedding, or the more commonly used Third Collection Embedding.