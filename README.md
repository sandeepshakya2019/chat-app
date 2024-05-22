
# Chat App

This is the chat app created using MERN Technology.

Frontend: ReactJS, Redux, React-router, Socket.io, Material UI    
Backend: NodeJS, ExpressJs, Socket.io

Database: MongoDB (Mongoose as ODM)

## Video related to the app

https://github.com/sandeepshakya2019/chat-app/assets/51978973/f71f841c-342c-4cbc-8628-9666fb7a5b03

## To Run the backend : 

1) Download the backend folder
2) Create a .env file using a .sampleenv file which contains 
   (before this register on Cloudinary )
  
MONGO_URI = mongodb://localhost:27017  
JWT_SECRET= secret token  
ADMIN_SECRET_KEY= admin secret key

NODE_ENV = DEVELOPMENT
CLIENT_URL = http://localhost:3000

CLOUDINARY_CLOUD_NAME= cloud name   
CLOUDINARY_API_KEY = API key    
CLOUDINARY_API_SECRET =  API secret key

3) Run the MongoDB database on localhost
4) do the "npm install" this will install all the dependency
5) Enter the command "npm run dev" 

## To Run the Frontend

1) Just download the Frontend folder
2) do the "npm i" this will install the dependency
3) Enter the command "npm run start" 



