## Welcome to Cookbook

### Short Description

Web app for recipes. Enjoy!

### Technologies

MERN stack app (MongoDB, Express, React and NodeJS with Mongoose)

### To run it you should

- git clone https://github.com/MirsadZagrljaca/cookbook
- cd client && npm install && npm start and open browser at localhost:3000
- cd server && npm install && npm start

### Testing accounts

#### regular user
-   user@user.u
-   useruser

### Dependecies

#### backend

##### devDependencies

- babel-core
- babel-loader
- babel-preset-env
- babel-preset-stage-2
- nodemon
- webpack
- webpack-cli
- webpack-node-externals

##### dependencies

- body-parser
- compression
- cookie-parser
- cors
- crypto
- dot-env
- express
- express-jwt
- helmet
- jsonwebtoken
- lodash
- mongoose

#### frontend

- axios
- bootstrap
- crypto
- prop-types
- react
- react-bootstrap
- react-dom
- react-google-charts
- react-google-login
- react-router
- react-router-dom
- react-scripts
- react-vis
- web-vitals

### File names explained

#### backend

- config.js - config variables
- auth.controller.js - crud operations for auth route
- cache.controller.js - crud operations for cached users
- recipe.controller.js - crud operations for recipes
- user.controller.js - crud operations for users
- dbErrorHelper.js - error messages from db
- recipe.model.js - mongoose schema for recipe
- user.models.js - mongoose schema for users
- routes.js - routing for backend
- express.js - express file
- server.js - main file
- template.js - template for sending to browser
- multer.middleware.js - multer file for uploading pictures

#### frontend

- assets - picture used in app
- Header.js - header
- Home.js - home page
- Create.js - account creating modal
- Signin.js - login modal
- AddRecipe.js - Component for adding recipes
- EditProfile.js - edit profile
- EditRecipe.js - edit recipe
- MyProfile.js - profile route
- MyRecipes.js - myrecipes route
- SingleRecipe.js - displaying single recipe
- recipe-api.js - crud for recipes
- auth-api.js - auth operations
- auth-helper.js - auth helpers

#### cache

- cachedUser.js - object that servs function of cache for app