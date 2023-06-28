# nosql-challenge
Module 12 Challenge


### Search records in a MongoDB database and return specific fields only:
- ChatGPT helped me form code to search for record with BusinessType "Restaurant/Cafe/Canteen" and return only the BusniessType and BusinessTypeID fields.
- ![image](https://github.com/nickpalmer2012/nosql-challenge/assets/128104435/65a602e8-90a4-4500-89ad-636eb00c366d)

- I went ahead and looked at the documentation to help my understanding: https://www.mongodb.com/docs/manual/reference/method/db.collection.find/#mongodb-method-db.collection.find
- I learned that you can use the "find" function to look for fields that match a condition that I specify by entering my query into a dictionary within the "find" function.
-  I then can add another dictionary that specifies the fields I want to return with my query by adding a comma to the end of the first dictionary that searches for records with the specified conditions. I then add another dictionary that specifies which fields I want the query to return by pairing the field type with a "1".

-  I learned in the documentation that the ID number will be included in any query by default, so it is necessary to add "_id":0, so that only the BusinessType and BusinessTypeID show in the result.


### Delete all records with "Dover" local authority name:
- ChatGPT helped me get the following example code to create a deleted records variable, then return the number of deleted records to see if it matches the count of the query above.
- ![image](https://github.com/nickpalmer2012/nosql-challenge/assets/128104435/f9b0f98d-eedb-4584-acdd-483ec73ba85e)
- ![image](https://github.com/nickpalmer2012/nosql-challenge/assets/128104435/b383f9dd-e41c-4585-a2d1-eba2ba6788e2)


### Search for establishments with RatingValue greater than or equal to:
https://www.mongodb.com/docs/manual/reference/operator/query/gte/
