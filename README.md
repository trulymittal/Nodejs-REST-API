# RESTful API

This is a RESTful API example based on Node.js and MongoDB, following the **MVC pattern** i.e. Model ~~View~~ Controller.

**Mongoose** is used for Database transactions which is an elegant solution to mongodb object modeling for node.js.

The application is **production ready**, and can be used behind a Nginx reverse proxy securely.

---

#### To start setting up the project

Step 1: Clone the repo

```bash
git clone https://github.com/trulymittal/Nodejs-REST-API.git
```

Step 2: cd into the cloned repo and run:

```bash
npm install
```

Step 3: Put your credentials in the .env file.

```bash
PORT=3000
MONGODB_URI=YOUR MONGODB URI
DB_NAME=DATABASE NAME OF YOUR CHOICE
DB_USER=DATABASE USER
DB_PASS=DATABASE USER PASSWORD 
```

Step 4: Start the API by

```bash
npm start
```

## Author

- [**Truly Mittal**](https://trulymittal.com)

## License

This project is licensed under the MIT License.
