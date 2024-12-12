# Role Based Access Control (...still in dev mode...)

This project is a Role-Based Access Control (RBAC) system built with Node.js, Express, and Passport.js, providing a strong foundation for applications that require secure authentication and authorization mechanisms.

Key Highlights:
User Authentication: Currently supports Email & Password login. Additional authentication methods such as OAuth/OAuth2.0 (Google, Facebook, GitHub, Apple, etc.) can be easily integrated if needed.
Access Control: Implements role-based permissions to ensure users can only access authorized resources.
Scalable Architecture: Designed using the MVC (Model-View-Controller) structure for improved code organization and scalability.
Database Support: Uses MongoDB with Mongoose as an ORM for efficient user data management.
Authentication Library: Leverages Passport.js for seamless local authentication.

---

## To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/Rahulsingh-128/VRV_Security_Project.git
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
```


## Contribute

You can fork this repo and send me a PR.

## License

This project is licensed under the MIT License.
