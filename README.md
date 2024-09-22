
# Connectify - Messaging Service Prototype
## Documentation
Connectify is a cutting-edge messaging service chat application that allows users to authenticate  designed to showcase secure, real-time communication with modern features like chat one-on-one, and create group chats. This project includes user authentication, one-on-one and group chats, real-time messaging. It's built with scalability, performance, and user experience in mind.

## My Introduction
Name - **Rajendra kumar**, College - **Indian Institute of Technology (IIT) Mandi**, 

## Table of Contents
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Running the Application](#running-the-application)
- [System Design](#system-design)


## Features
- **User Authentication(signup/login)**: Secure sign-up and login using JWT for session management.
- **Text Messaging**: Send and receive real-time text messages between users.
- **Group Chat functionality**: Create and participate in group chats with multiple users.
- **Real-Time Updates**:Messages are delivered and updated instantly using Socket.IO.
- **Search User**: Quickly find users by name or other identifiers.
- **Single Chat(One-on-one chat)**: Engage in private one-on-one chat sessions.

## Screenshots

**Sign-up/Login (User Authentication Screen)**
![image](https://github.com/user-attachments/assets/423974b5-45c9-4099-88a5-a66bb4687261)
![image](https://github.com/user-attachments/assets/9fb7edd2-b825-4ab9-bfce-aa5e2630cc64)
![image](https://github.com/user-attachments/assets/3261597f-3cf0-4c5e-bddf-ae018a6894f4)




**Chats Screen**
![image](https://github.com/user-attachments/assets/ea4717c2-359e-409f-bb4c-d99a35893e7e)
![image](https://github.com/user-attachments/assets/0852532a-f89a-4411-81e7-d2d46e69a13a)

**Search User And Initialize Chat**
![image](https://github.com/user-attachments/assets/1dab8dff-9640-4b1b-a770-0a2debb311b9)
![image](https://github.com/user-attachments/assets/7c3e1bfc-a42d-4d8f-a6a2-bcc18e44be9d)
![image](https://github.com/user-attachments/assets/a6b571d4-73e9-46e4-9b80-7c2db98b9622)
![image](https://github.com/user-attachments/assets/55b7cc36-d8e0-47da-b601-cd76352ae185)


**Group Chat Screen**
![image](https://github.com/user-attachments/assets/565b8567-db53-4317-888b-6570b62b7520)
![image](https://github.com/user-attachments/assets/0e319fdf-2eed-4f22-8b06-145ece556406)
![image](https://github.com/user-attachments/assets/3f810d5e-4ab2-4272-a829-79781a302199)

**Real-Time Chat Screen**
![image](https://github.com/user-attachments/assets/44a5ced0-4c24-484a-bf74-7ab23598ad68)
![image](https://github.com/user-attachments/assets/272d0345-24c8-4629-99c3-d7dbd00439e3)
![image](https://github.com/user-attachments/assets/72a6ecb1-35e6-44ad-8445-c10e3c86eb44)


**Notifications & Log out Screen**
![image](https://github.com/user-attachments/assets/46d0ec71-4e45-48cf-b2df-6b094ca55d3c)
![image](https://github.com/user-attachments/assets/469432f2-24f3-463a-8643-fba792fed8ba)


## Technologies Used
- **Backend**: Node.js, Express.js, MongoDB, Socket.IO
- **Frontend**: React.js, Chakra UI for a responsive UI
- **Real-Time Updates**: Socket.IO for real-time communication
- **Dev Tools**: Nodemon for server management, JWT for authentication, Mongoose for MongoDB interaction
- **Platforms**: VS Code, Postman, MondoDB.

  
## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/rajendra-17/Connectify.git
   cd Connectify

2. **Install Root Dependencies**:
   ```bash
   npm install --legacy-peer-deps

  ## List of Root Dependencies:

    bcryptjs: ^2.4.3
    colors: ^1.4.0
    dotenv: ^16.4.5
    express: ^4.21.0
    express-async-handler: ^1.2.0
    jsonwebtoken: ^9.0.2
    mongoose: ^8.6.3
    nodemon: ^3.1.5
    react-scripts: ^4.0.3
    socket.io: ^4.7.5
    socket.io-client: ^4.7.5



3. **Install Frontend Dependencies**:
   ```bash
   cd frontend
   npm install --legacy-peer-deps

  ## List of Frontend Dependencies:

    @chakra-ui/icons: ^2.1.1
    @chakra-ui/react: ^2.8.2
    @emotion/react: ^11.13.3
    @emotion/styled: ^11.13.0
    @testing-library/jest-dom: ^5.17.0
    @testing-library/react: ^13.4.0
    @testing-library/user-event: ^13.5.0
    axios: ^1.7.7
    framer-motion: ^11.5.4
    react: ^18.3.1
    react-dom: ^18.3.1
    react-lottie: ^1.2.4
    react-notification-badge: ^1.5.1
    react-router-dom: ^5.3.4
    react-scripts: 5.0.1
    react-scrollable-feed: ^2.0.2
    react-toastify: ^10.0.5
    socket.io-client: ^4.7.5
    web-vitals: ^2.1.4

 
4. **Set Up Environment Variables**
   Create a .env file in the root directory of the project and add your personal environment variables:
      ```bash
      PORT=5000
      MONGO_URI=*********
      JWT_SECRET=*****
      NODE_ENV=****
      DISABLE_ESLINT_PLUGIN=***

5. **Running the Project**
   To start the server, run the following command in the root directory:
      ```bash
      npm start

   To start the frontend, run:
      ```bash
      cd frontend
      npm start
Open Localhost on port 3000 in your browser and enjoy **CONNECTIFY**, Cheers!

## System Design
The Connectify messaging system is built using a scalable architecture to support high traffic, real-time messaging:
- **Backend**: RESTful APIs using Express.js for handling authentication, message routing, and group management.
- **Real-Time Messaging**: Socket.IO ensures real-time communication for both individual and group chats.
- **Database**: MongoDB is used for its flexibility and scalability, storing users, messages, and chat information.
- **Security**: JWT is used to manage secure authentication sessions. Sensitive information like passwords is hashed using bcrypt.
- **Platforms**: VS Code, Postman, MondoDB.
