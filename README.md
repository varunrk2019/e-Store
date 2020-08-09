## Run Locally

### 1. Clone repo

```
$ git clone git@github.com:varunrk2019/e-Store.git
$ cd e-Store
```

### 2. Install MongoDB

Download it from here: https://docs.mongodb.com/manual/administration/install-community/

### 3. Run Frontend

```
# open new terminal
$ cd frontend
$ npm install
$ npm run build
```

### 4. Run Backend

```
$ npm install
$ npm start
```



### 5. Create Admin User

- Run this on chrome: http://localhost:9002/api/users/createadmin
- It returns admin email and password

### 6. Login

- Run http://localhost:9002/signin
- Enter admin email and password and click signin

### 7. Create Products

- Run http://localhost:9002/products
- Click create product and enter product info
