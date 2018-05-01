## node-passport-jwt-example-app

#### 1) Go to the project folder
#### 2) npm install
#### 3) npm start

#### Make a post request to login, use `localhost:3000/auth/login/`
#### Credentials:
##### name: `javier`
##### password: `password123`
- You can use Postman


#### Test the authentication, use `localhost:3000/auth/secret/` 
#### Header:
##### key: `Authorization`
##### value: `Bearer ` + token

Example: 
Login:
![alt text](https://raw.githubusercontent.com/jmchaves/node-passport-jwt-example-app/master/public/images/login.png)

Get secret message:
![alt text](https://raw.githubusercontent.com/jmchaves/node-passport-jwt-example-app/master/public/images/success-message.png)
