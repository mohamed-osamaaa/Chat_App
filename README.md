


https://github.com/user-attachments/assets/a523ee1b-8fad-4be7-88d3-287e130ecc72



https://github.com/user-attachments/assets/41682e1c-23c9-44f2-b4b2-fdb448949948


---

# Chat_App

## About

**Chat_App** is a modern real-time chat application built using the MERN stack (MongoDB, Express, React, Node.js), along with Socket.io for real-time messaging, and TailwindCSS with Daisy UI for a responsive and sleek design. This app allows users to send both text and image messages, change their theme and profile photo, and check the online status of users. It also includes JWT-based authentication, validation, and enhanced user experience features. 

Key features include:
- **Real-time messaging** with Socket.io
- **Authentication & Authorization** using JWT
- **User management** with email and strong password (hashed in the database)
- **Profile customization** (change photo and theme)
- **Cloudinary integration** for image uploading
- **Global state management** with Zustand
- **Responsive design** using TailwindCSS and Daisy UI
- **Error handling** on both the server and client sides
- **Online user status tracking**
- **Toast Notifications** for success and error messages

## Tech Stack

- **Frontend**: React.js, TailwindCSS, Daisy UI
- **Backend**: Node.js, Express
- **Database**: MongoDB
- **Real-time communication**: Socket.io
- **Authentication**: JWT (JSON Web Tokens)
- **File Upload**: Cloudinary

## Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/mohamed-osamaaa/Chat_App.git
   cd Chat_App
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Create a `.env` file** in the root of your project and add the following configuration:

   ```
   MONGODB_URI=your_mongodb_connection_string
   PORT=5001
   JWT_SECRET=your_jwt_secret
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   NODE_ENV=development
   ```

4. **Build the app**:
   ```bash
   npm run build
   ```

5. **Start the app**:
   ```bash
   npm start
   ```

## Features

- **Authentication**: 
  - **Login** with email and password.
  - **Registration** with full name, email, and password.
  - **Password hashing** for security.

- **Real-time Messaging**: 
  - Send and receive text messages in real-time.
  - Send and receive image messages.

- **Profile Management**: 
  - Change profile picture and theme.
  
- **Cloudinary Integration**: 
  - Upload images (profile photo and messages) to Cloudinary.

- **Online Status**: 
  - See which users are currently online.

- **Error Handling**: 
  - Handles errors both on the client and server sides for smooth user experience.

- **Global State Management**:
  - Zustand for managing global app state.

---

