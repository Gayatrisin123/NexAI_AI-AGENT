{"app.js": "import express from 'express';
const app = express();
app.get('/', (req, res) => {
    res.send('Hello World!');
});
app.listen(3000, () => {
    console.log('Server is running on port 3000');
});", "package.json": "{
    \"name\": \"express-server\",
  \"version\": \"1.0.0\",
  \"description\": \"Express server with ES6 features\",
  \"main\": \"app.js\",
  \"type\": \"module\",
  \"scripts\": {
      \"start\": \"node app.js\"
  },
  \"keywords\": [
      \"express\",
    \"es6\",
    \"server\"
  ],
  \"author\": \"Your Name\",
  \"license\": \"ISC\",
  \"dependencies\": {
      \"express\": \"^4.18.2\"
  }
}"}