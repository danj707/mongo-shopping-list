# mongo-shopping-list v1.0

##Shopping List project using Node.js/express backend, tests with mocha/chai, database by mongodb/mongoose

###Index.html
* Frontend allows viewing of db objects, editing, adding new entries, deleting entries

###server.js
*Provides REST API endpoints to database for standard CRUD procedures via http
  1. GET /items - gets a list of the items in database
    ![shopping list](http://i.imgur.com/jmWJRSbm.png "Shopping List")
  
  2. POST /items/id - adds a new item to the database
   ![shopping list](http://i.imgur.com/UDjZTU4m.png "Shopping List")
   
  3. PUT /items/id - updates the item in the database
   ![shopping list](http://i.imgur.com/QKnbAblm.png "Shopping List")
   
  4. DELETE /items - deletes the item from the database
 ![shopping list](http://i.imgur.com/ExJgAsDm.png "Shopping List")

###test-server.js
*Provides testing of API endpoints using mocha/chai

###Future Enhancements
  1. Added functionality including: user logins, authentication, multiple lists
  2. Enhanced design and layout
  3. Saving of favorite items, including links/lists to stores
  4. Shopping Cart
