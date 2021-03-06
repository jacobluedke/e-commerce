# E-Commerse
  ## Description
  This functional Express.js API takes the user's MySQL username and password and a database name and adds them to an environment variable file. Then it connects to the database using sequelize. When schema and seed commands are entered, a development database is created and is seeded with test data. When the application is started via command, the server is started and the sequelize models are synced to the MySQL database. When the user opens API get routes in postman for categories, products or tags, the data for each of those routes is displayed in a formatted JSON. When the user test API post, put, and delete routes in postman then they are able to successfully create update and delete data in their database.
  ## Table of Contents
  [Installation](#installation)

  [Usage](#usage)

  [GitHub](#github)

  [Walkthrough](#walkthrough)
  
  ## Installation
  npm i
  ## Usage
  In terminal enter npm run seed to enter information into the database. 
  Then enter npm start to start up the server.js.
  ## GitHub

  Link to GitHub: [jacobluedke](https://github.com/jacobluedke)
  ## Walkthrough

  Link to categories walkthrough: [https://watch.screencastify.com/v/RUwCKZvaU2I1CpYcy7Hf](https://watch.screencastify.com/v/RUwCKZvaU2I1CpYcy7Hf)

  Link to products walkthrough: [https://watch.screencastify.com/v/0XHGKljEIeEx2lZdWuOq](https://watch.screencastify.com/v/0XHGKljEIeEx2lZdWuOq)

  Link to tags walkthrough: [https://watch.screencastify.com/v/bgTreSOaTFsF1A8bV2ZV](https://watch.screencastify.com/v/bgTreSOaTFsF1A8bV2ZV)
