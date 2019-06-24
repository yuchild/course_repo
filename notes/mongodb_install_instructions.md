## MongoDB Installation

1. To install MongoDB, use your operating system's package manager:

   - Mac OS X: `brew install mongodb`
   - Ubuntu Linux: `sudo apt-get install mongodb`

2. Much like Postgres, you will need to launch the server before using Mongo for the first time. 

   - Mac OS X: `brew services start mongodb`
   - Ubuntu Linux: `sudo /etc/init.d/mongodb start` 

3. Check your installation by opening the MongoDB Client:

   - Open a new terminal and type `mongo` to open up a Mongo shell
   - Type `show dbs;` to show the databases you have
   - You can exit by typing `exit`

4. Resources and quick references to Mongo commands:

   - [MongoDB Cheatsheet][mongo-cheatsheet]
   - [Mongo Docs][mongo-docs]
   - [MongoDB Reference Cards][mongo-ref-cards]

[mongo-cheatsheet]:https://blog.codecentric.de/files/2012/12/MongoDB-CheatSheet-v1_0.pdf
[mongo-docs]:http://docs.mongodb.org/v2.2/mongo/
[mongo-ref-cards]:http://semantic.supelec.fr/BigData/downloads/MongoDB-ReferenceCards15.pdf
