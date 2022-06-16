

## Description
This project is a summary of this back-end trimester: authentication, NodeJS, MongoDB, Redis, pagination and background processing.

---

### [0. Redis utils](./utils/redis.js)
* Inside the folder utils, create a file redis.js that contains the class RedisClient. RedisClient should have:


### [1. MongoDB utils](./utils/db.js)
* Inside the folder utils, create a file db.js that contains the class DBClient. DBClient should have:


### [2. First API](./server.js)
* Inside server.js, create the Express server. 


### [3. Create a new user](./routes/index.js)
* Now that we have a simple API, it’s time to add users to our database. In the file routes/index.js, add a new endpoint


### [4. Authenticate a user](./routes/index.js)
* In the file routes/index.js, add 3 new endpoints:


### [5. First file](./routes/index.js)
* In the file routes/index.js, add a new endpoint:


### [6. Get and list file](./routes/index.js)
* In the file routes/index.js, add 2 new endpoints:


### [7. File publish/unpublish](./routes/index.js)
* In the file routes/index.js, add 2 new endpoints:


### [8. File data](./routes/index.js)
* In the file routes/index.js, add one new endpoint:


### [9. Image Thumbnails ](./controllers/FilesController.js)
* Update the endpoint POST /files endpoint to start a background processing for generating thumbnails for a file of type image:

---

## Author
* **Hassan Juma** - [Hassan Juma](https://github.com/hassan1a)

# alx-files_manager
