mkdir client
cd client
npx create-react-app ./

mkdir server
cd server
npm init -y

npm install body-parser cors express mongoose nodemon

client-side:
npm install axios moment react-file-base64 redux redux-thunk