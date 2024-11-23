# VRV-assignment
This is a role-based access control application that uses Nodejs, Express, Passport Js, etc.

**Mongoose** is used as an ORM for MongoDB for storing Users in Database.

**Passport JS** is used for local(email, password) authentication.

The application is _almost_ **production ready**.


## To start setting up the project

Step 1: Clone the repo

```bash
git clone ---this repo link--
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR_MONGODB_URI(example: mongodb://localhost:27017)
DB_NAME=YOUR_DB_NAME
```

Step 4: Install MongoDB (Linux Ubuntu)

See <https://docs.mongodb.com/manual/installation/> for more infos

Step 5: Run Mongo daemon

```bash
sudo service mongod start
```

Step 6: Start the app by

```bash
npm start
