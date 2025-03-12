# Note Taking App

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
| Login Screen | ![Screenshot 2025-03-13 022523](https://github.com/user-attachments/assets/1473290f-542e-4eb1-9e00-3cdf9bfa30df) |

| Notes Dashboard | ![Screenshot 2025-03-13 022548](https://github.com/user-attachments/assets/7011a4b2-6532-4fac-a1fc-b1f06719fef0) |

| Create Note | ![Screenshot 2025-03-13 022559](https://github.com/user-attachments/assets/290a696c-20b7-4e8a-a596-919d4f2de1e1) |
| Backend View | ![Screenshot 2025-03-13 022627](https://github.com/user-attachments/assets/d0a79f82-9499-499e-8848-2fb95039f57c) |

*To add your screenshots:*
1. Create a `screenshots` folder in your repository
2. Add your application screenshots to this folder
3. Update the paths in the table above

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or above)
- Firebase account
- Git

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/note-taking-app.git
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

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgements

- [Firebase Documentation](https://firebase.google.com/docs)
- [MDN Web Docs](https://developer.mozilla.org/)
- [Font Awesome](https://fontawesome.com/) for icons
