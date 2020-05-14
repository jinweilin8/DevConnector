# DevConnector
Developer social network app using MERN stack. [Live demo](https://devconnector-jeremy.herokuapp.com/)

# Installing DevConnector

### Add a default.json file in config folder with the following

```
{
  "mongoURI": "<your_mongoDB_Atlas_uri_with_credentials>",
  "jwtSecret": "secret",
  "githubToken": "<yoursecrectaccesstoken>"
}
```
  
### Install server dependencies

```bash
npm install
```

### Install client dependencies

```
cd client
npm install
```

### Run both Express & React from root

```
npm run dev
```

# Acknowledgement
This app is based on Brad's [Udemy Course](https://www.udemy.com/course/mern-stack-front-to-back/)
