#### JOBS API

1. Node JS
2. Express  
3. MONGO_DB (Database)
4. Mongoose
5. Bcrypt JS
6. Json Web Token


#### Database Connection

1. Setting up connectDB function which takes in MONGO_URI as a parameter and connects to the MONGO Database
2. Invoked in start()


#### Routers

- auth.js
- jobs.js


#### User Model

- Setting up User Model using Mongoose  
- Email Validation using Regex
 

#### Job Model

- Setting up Job Model using Mongoose  


#### Register User

- Validate - name, email, password - with Mongoose
- Hash Password (with bcryptjs)
- Save User
- Generate Token
- Send Response with Token


#### Login User

- Validate - email, password - in controller
- If email or password is missing, throw BadRequestError
- Find User
- Compare Passwords
- If no user or password does not match, throw UnauthenticatedError
- If correct, generate Token
- Send Response with Token


#### Mongoose Errors

- Validation Errors
- Duplicate (Email)
- Cast Error


#### Security

- helmet
- cors
- xss-clean
- express-rate-limit

