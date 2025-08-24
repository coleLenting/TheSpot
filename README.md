# The Spot
`Commands Ran for Directory`
## 1. Backend (Express.js + MongoDB)
### Create backend folder
    mkdir backend
    cd backend

### Init Node project
    npm init -y

### Install core dependencies
    npm install express mongoose cors dotenv bcryptjs jsonwebtoken

### Install dev dependencies
    npm install --save-dev nodemon

## 2. Frontend (Angular Web)
    cd ..
    ng new frontend --routing --style=scss
    cd frontend

# Issues with Tailwind, maybe use Bootstrap
    npm install bootstrap

## 3. Mobile (React Native with Expo)
npx create-expo-app mobile
cd mobile

# Install navigation + dependencies
npm install @react-navigation/native
npm install @react-navigation/bottom-tabs @react-navigation/stack
npm install react-native-screens react-native-safe-area-context
npm install react-native-gesture-handler react-native-reanimated

# Install API + storage
npm install axios
npm install @react-native-async-storage/async-storage

