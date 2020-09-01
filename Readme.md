## React Native - Api

https://www.npmjs.com/package/json-server#getting-started


## Create api with dynamic data
mkdir api
cd api 

npm init -y
npm install json-server casual --save-dev

run 

node index.js

 
## Another method with db.json

npm install -g json-server
json-server --watch db.json
json-server -H 192.168.0.75 --watch db.json



 http://localhost:3000/posts/1,
