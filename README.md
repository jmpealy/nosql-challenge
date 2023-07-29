# nosql-challenge useful links

#https://www.tutorialspoint.com/mongodb/mongodb_query_document.htm
This helped to clear things up a bit more for me on query syntax in mongodb

#https://www.w3schools.com/python/python_mongodb_update.asp
More help with syntax in mongodb - this time for updating values 

#https://developerslogblog.wordpress.com/2019/10/15/mongodb-how-to-filter-by-multiple-fields/
I used this in the NoSQL analysis file when I was creating the queries for questions 2 and 3.

https://stackoverflow.com/questions/61456784/pymongo-cannot-encode-object-of-type-decimal-decimal
I used this when converting the latitude and longitude to a decimal number.  I tried $toDecimal but it didn't seem to be correct given that it had text before it.  $toDouble worked corretly which makes sense given it's basically the equivalent of a 'float' data type.



