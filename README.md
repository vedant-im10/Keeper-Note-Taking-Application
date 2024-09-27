# 📝 Keeper - Note Taking Application

**Keeper** is a full-stack **Note-Taking Application** that allows users to securely manage their personal notes. This application offers features such as creating, editing, and deleting notes, with user authentication to ensure that only authorized users can access their notes. The project is built with **React.js** on the frontend, **Node.js** and **Express.js** on the backend, and **MongoDB** for storing user data.

## 🌟 Features

- **🔐 User Authentication**: The app requires users to log in to access their notes. Each user has a unique account with secure session management.
- **📝 Note Creation**: Users can create new notes or lists using a simple, clean interface.
- **✏️ Edit and Delete Notes**: Users can edit and delete their notes at any time.
- **🗂️ User-Specific Content**: Each user can only see their own notes, ensuring privacy and security.
- **📋 Lists and Texts**: Users can create text-based notes or checklists, depending on their needs.

## 🔧 How It Works

1. **Login System**: Users need to log in to access the application. Without authentication, the app is inaccessible.
2. **Create, Edit, Delete Notes**: Once logged in, users can create notes, edit them, and delete them. The notes are stored securely in a database and linked to each user's account.
3. **User-Specific Access**: Each user has access only to their own notes. Even if multiple users are logged in, they cannot see each other's notes.

## 🛠️ Tech Stack

- **Frontend**: React.js (for dynamic UI and smooth interactions)
- **Backend**: Node.js, Express.js (for handling API requests and authentication)
- **Database**: MongoDB (for storing user data and notes)
- **Styling**: Custom CSS (for designing the UI)
