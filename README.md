# Note Taking App

<img src="https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/12cbe8a4-f55c-4b40-85bb-d8e1405e7b84/dj0xdez-4eda16a3-692d-470a-a006-31cd013b4e97.gif?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzEyY2JlOGE0LWY1NWMtNGI0MC04NWJiLWQ4ZTE0MDVlN2I4NFwvZGoweGRlei00ZWRhMTZhMy02OTJkLTQ3MGEtYTAwNi0zMWNkMDEzYjRlOTcuZ2lmIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.-vgia6h_JRVXXelFnMDK68MCPwA1kEel2w5YluYTqjE" />

A responsive web application for creating, organizing, and managing notes with real-time cloud synchronization using Firebase.




## 📝 Overview

This Note Taking App offers a clean, intuitive interface for capturing your thoughts, ideas, and important information. Built with HTML, CSS, and JavaScript with Firebase integration for backend functionality and data persistence.

## ✨ Features

- **User Authentication**: Secure login and registration system
- **Create & Edit Notes**: Rich text formatting options
- **Organize Notes**: Create categories or tags for better organization
- **Real-time Sync**: Notes automatically sync across devices
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Search Functionality**: Quickly find notes by content, title, or tags
- **Cloud Storage**: All notes securely stored in Firebase

## 🛠️ Tech Stack

<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="70" height="70"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="70" height="70"/>
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="70" height="70"/>
  <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="70" height="70"/>
</p>

## 📸 Screenshots

| Feature | Screenshot |
|---------|------------|
| Login Screen | ![Screenshot 2025-03-13 131121](https://github.com/user-attachments/assets/36b65ede-fc93-4e11-a0dd-6be68e9243f8) |
| Notes Dashboard | ![Screenshot 2025-03-13 131105](https://github.com/user-attachments/assets/5180a7df-852c-4b2f-9c8c-a009268623e6) |
| Create Note | ![Screenshot 2025-03-13 125158](https://github.com/user-attachments/assets/34e835f2-3d0c-49b4-9498-0de7a2bd7117) |
| Backend View | ![Screenshot 2025-03-13 022627](https://github.com/user-attachments/assets/d0a79f82-9499-499e-8848-2fb95039f57c) |

## 📝 Videos

https://github.com/user-attachments/assets/0eed946b-3157-4910-b308-aae34140cd5e



https://github.com/user-attachments/assets/91b9c18f-aca5-4ccc-a2f4-29723ff2ecb6



https://github.com/user-attachments/assets/853dc681-cd4b-4ee9-b99b-d89479d08632









## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or above)
- Firebase account
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/aliiakbarkhan/note-taking-app.git
   cd note-taking-app
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Configure Firebase:
   - Create a Firebase project at [https://console.firebase.google.com/](https://console.firebase.google.com/)
   - Enable Authentication and Firestore
   - Add a web app to your Firebase project
   - Copy the Firebase configuration
   - Create a `.env` file in the root directory and add your Firebase config:
     ```
     FIREBASE_API_KEY=your-api-key
     FIREBASE_AUTH_DOMAIN=your-auth-domain
     FIREBASE_PROJECT_ID=your-project-id
     FIREBASE_STORAGE_BUCKET=your-storage-bucket
     FIREBASE_MESSAGING_SENDER_ID=your-messaging-sender-id
     FIREBASE_APP_ID=your-app-id
     ```

4. Run the application:
   ```
   npm start
   ```

## 📱 Usage

1. Register or log in to your account
2. Create a new note by clicking the "+" button
3. Edit your note in the editor
4. Apply formatting or add tags as needed
5. Notes are automatically saved and synced
6. Search for notes using the search bar
7. Organize notes using the category system

## 🔧 Configuration

You can customize various aspects of the application in the `config.js` file:
- Theme settings
- Editor options
- Default categories
- User preferences

## 📊 Project Structure

```
note-taking-app/
├── public/
│   ├── index.html
│   ├── favicon.ico
│   └── assets/
├── src/
│   ├── js/
│   │   ├── app.js
│   │   ├── auth.js
│   │   ├── firebase.js
│   │   └── notes.js
│   ├── css/
│   │   ├── main.css
│   │   ├── auth.css
│   │   └── responsive.css
│   └── components/
│       ├── editor.js
│       ├── sidebar.js
│       └── modal.js
├── .env
├── package.json
├── README.md
└── LICENSE
```

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License



https://github.com/user-attachments/assets/1b6f530c-0eb8-4c25-90c6-f26a9c64263a



## 👏 Acknowledgements

- [Firebase Documentation](https://firebase.google.com/docs)
- [MDN Web Docs](https://developer.mozilla.org/)
- [Font Awesome](https://fontawesome.com/) for icons
