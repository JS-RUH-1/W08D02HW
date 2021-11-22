# Mongo DB shell
### For each step take a shot and when you are done upload the results as pdf file
[Mongo Shell](https://www.bmc.com/blogs/mongo-shell-basic-commands/)

[Mongodb guide](https://docs.mongodb.com/guides/)

- Create a collection called resturants
- insert one resturant into the resturants collection, for example:

```
{ "name": "Albaik", "city": "Jeddah", "score": 10 }
```

- insert many resturants into the resturants collection, for example:

  ````
  { "name": "AlTazaj","city": "Makkah", "score": 9 },
  { "name": "KFC","city": "AlMadinah", "score": 8 },
  { "name": "Dominos pizza","city": "Jeddah", "score": 9.5 },
  { "name": "Baba Khan","city": "Jeddah", "score": 9 },
  { "name": "Krispy Kreme","city": "Riyadh", "score": 8.5 }
  ````

- Display all the documents in the collection restaurants.
- Display all the documents in the collection restaurants, but exclude the field _id.
- Display all the restaurants which is in Jeddah city.
- Display all the restaurants which is achieved a score grater than or equal to 9.
- Display all the restaurants which is achieved a score grater than or equal to 8 but less than 9.5.
- Display all the restaurants which is in Jeddah and achieved a score grater than or equal to 9.5.
- Display all the restaurants which is contain 'Al' as first two letters of its name.
- Display all the restaurants which is contains 'k' somewhere in its name, either k is big or small.
- Display all the restaurants by arranged the name of the restaurants in ascending order.
- Update Dominos pizza resturant which is in Jeddah to be in AlMadinah, and the name to Dominos Pizza, and the score to 10
- Delete the KFC restaurant
