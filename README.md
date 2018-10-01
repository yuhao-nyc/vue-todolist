# todolist-assignment

## To run the project
``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# run unit test
npm run unit

# build for production with minification
npm run build
```

Notes:
1. there's some issue with the unit testing framework in this repo. so i started some pseudo code unit test for now. it still needs changes and improvements
2. for the user sign up/login for now I used Vuex store to temporary store them in the client side. will be removed after page refresh.
3. I should be able to set up Firebase with Vuex to make a user profile signup/login
4. should divide the authbox component to more modular component. like sign up and login should be seperated