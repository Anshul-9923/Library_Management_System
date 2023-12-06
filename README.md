# Library_Management_System

## Run Locally

### Clone the project

```bash
  git clone https://github.com/Anshul-9923/Library_Management_System
```
### Go to the Backend of project directory

```bash
  cd Library_Management_System/Backend
```

### Install dependencies and generate .env file

```bash
   npm install
   touch .env
```
In this .env file enter the following data:  
MONGO_URL = "//Paste Your Localhost MongoDB Atlas URL here// "  
PORT = 3001  
CLOUD_NAME = "//Enter your cloudinary cloud name"  
API_KEY = "//Enter your cloudinary api key"  
API_SECRET = "//Enter your api_secret key"


### Start the server

```bash
  npm run dev
```

### Go to the Frontend of the project directory

```bash
  cd Library_Management_System/Frontend
```

### Install dependencies and generate a .env file

```bash
   npm install
   touch .env
```
In this .env file enter the following data:  
VITE_BASE_URL = "http://localhost:3001/"

### Start the server

```bash
  npm run devserver
```
Go to http://localhost:5173 in any browser to see the application running.

```bash
  npm run devserver
```
Go to http://localhost:5173 in any browser to see the application running.

