# React Firebase Super Chat 🚀

A modern, real-time chat application built with React and Firebase. Experience seamless messaging with a beautiful UI and powerful features.

## ✨ Features

- 💬 Real-time messaging
- 🔐 User authentication
- 👥 Multiple chat rooms
- 🎨 Modern and responsive UI
- 📱 Mobile-friendly design
- 🔔 Message notifications
- 📸 Image sharing support
- 🎯 Emoji support

## 🎥 Demo

Check out the live demo: [Super Chat Demo](https://superchat-lemon.vercel.app)

## 🛠️ Tech Stack

- React.js
- Firebase (Authentication, Firestore, Storage)
- Tailwind CSS
- React Router
- React Icons

## 🚀 Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Firebase account

### Installation

1. Clone the repository
```bash
git clone https://github.com/anishumar/superchat.git
cd superchat
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Set up environment variables
```bash
# Copy the example environment file
cp .env.example .env

# Edit .env with your Firebase configuration
# Never commit .env to version control!
```

4. Set up Firebase
   - Create a new Firebase project
   - Enable Authentication, Firestore, and Storage
   - Add your Firebase configuration to `.env`

5. Start the development server
```bash
npm start
# or
yarn start
```

## 📝 Environment Variables

The following environment variables are required:

```env
REACT_APP_FIREBASE_API_KEY=your_api_key
REACT_APP_FIREBASE_AUTH_DOMAIN=your_auth_domain
REACT_APP_FIREBASE_PROJECT_ID=your_project_id
REACT_APP_FIREBASE_STORAGE_BUCKET=your_storage_bucket
REACT_APP_FIREBASE_MESSAGING_SENDER_ID=your_messaging_sender_id
REACT_APP_FIREBASE_APP_ID=your_app_id
```

### Security Notes

- Never commit `.env` to version control
- Keep your API keys secure
- Use environment variables for all sensitive data
- For production, set environment variables in your hosting platform (Vercel, Netlify, etc.)

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Fireship](https://fireship.io/) for the amazing tutorial
- [React](https://reactjs.org/)
- [Firebase](https://firebase.google.com/)