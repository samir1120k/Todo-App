# 📱 Modern Todo App

<div align="center">

![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-1C1E24?style=for-the-badge&logo=expo&logoColor=#D04A37)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-FF6B35?style=for-the-badge&logo=convex&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

A beautiful, modern todo application built with React Native and Expo, featuring real-time synchronization, dark/light themes, and an intuitive user interface.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

</div>

---

## ✨ Features

### 🎨 **Beautiful UI/UX**

- **Modern Design**: Clean, minimalist interface with gradient backgrounds
- **Dark/Light Theme**: Automatic theme switching with smooth transitions
- **Responsive Layout**: Optimized for all screen sizes
- **Smooth Animations**: Fluid interactions and transitions

### 📝 **Todo Management**

- ✅ **Add Todos**: Create new tasks with a simple input
- ✏️ **Edit Todos**: Inline editing with save/cancel options
- 🗑️ **Delete Todos**: Remove tasks with confirmation dialog
- 🔄 **Toggle Completion**: Mark tasks as complete/incomplete
- 📊 **Progress Tracking**: Visual progress statistics

### 🔧 **Advanced Features**

- 🌐 **Real-time Sync**: Live updates across devices using Convex
- 📱 **Cross-platform**: Works on iOS, Android, and Web
- 🔐 **Authentication**: Firebase Auth integration
- 📈 **Analytics**: Crash reporting with Firebase Crashlytics
- 💾 **Offline Support**: Works without internet connection

### ⚙️ **Settings & Customization**

- 🎯 **Progress Statistics**: Track your productivity
- 🌙 **Theme Preferences**: Customize appearance
- ⚠️ **Danger Zone**: Clear all todos option
- 🔧 **App Preferences**: Various customization options

---

## 🛠️ Tech Stack

### **Frontend**

- **React Native** - Cross-platform mobile development
- **Expo** - Development platform and tools
- **TypeScript** - Type-safe JavaScript
- **Expo Router** - File-based navigation
- **React Navigation** - Navigation library

### **Backend & Database**

- **Convex** - Real-time backend-as-a-service
- **Firebase Auth** - User authentication
- **Firebase Crashlytics** - Error tracking

### **UI/UX Libraries**

- **Expo Linear Gradient** - Beautiful gradient backgrounds
- **Expo Vector Icons** - Icon library
- **React Native Reanimated** - Smooth animations
- **React Native Gesture Handler** - Touch interactions

### **Development Tools**

- **ESLint** - Code linting
- **TypeScript** - Static type checking
- **EAS Build** - App building and deployment

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- [Node.js](https://nodejs.org/) (v18 or later)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)
- [Expo CLI](https://docs.expo.dev/get-started/installation/)
- [Git](https://git-scm.com/)

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Set up Convex**

   ```bash
   npx convex dev
   ```

4. **Configure Firebase**
   - Add your `google-services.json` file to the root directory
   - Update Firebase configuration in your project

5. **Start the development server**

   ```bash
   npm start
   # or
   yarn start
   ```

6. **Run on your preferred platform**

   ```bash
   # iOS Simulator
   npm run ios

   # Android Emulator
   npm run android

   # Web Browser
   npm run web
   ```

---

## 📱 Screenshots

<div align="center">

### Home Screen

![Home Screen](https://via.placeholder.com/300x600/4A90E2/FFFFFF?text=Home+Screen)

### Settings Screen

![Settings Screen](https://via.placeholder.com/300x600/7ED321/FFFFFF?text=Settings+Screen)

### Dark Theme

![Dark Theme](https://via.placeholder.com/300x600/2C3E50/FFFFFF?text=Dark+Theme)

</div>

---

## 📁 Project Structure

```
├── app/                    # App screens and navigation
│   ├── (tabs)/            # Tab navigation screens
│   │   ├── index.tsx      # Home/Todo screen
│   │   └── setting.tsx    # Settings screen
│   └── _layout.tsx        # Root layout
├── components/            # Reusable UI components
│   ├── Header.tsx         # App header
│   ├── TodoInput.tsx      # Todo input component
│   ├── EmptyState.tsx     # Empty state component
│   ├── LoadingSpinner.tsx # Loading indicator
│   ├── ProgressStats.tsx  # Progress statistics
│   ├── Preferences.tsx    # User preferences
│   └── DangerZone.tsx    # Danger zone settings
├── convex/               # Backend functions and schema
│   ├── schema.ts         # Database schema
│   └── todos.ts          # Todo CRUD operations
├── hooks/                # Custom React hooks
│   └── useTheme.tsx      # Theme management hook
├── assets/               # Static assets
│   ├── images/          # App images and icons
│   └── styles/          # Style definitions
└── android/             # Android-specific files
```

---

## 🔧 Available Scripts

| Script            | Description                       |
| ----------------- | --------------------------------- |
| `npm start`       | Start the Expo development server |
| `npm run android` | Run on Android emulator/device    |
| `npm run ios`     | Run on iOS simulator/device       |
| `npm run web`     | Run in web browser                |
| `npm run lint`    | Run ESLint for code quality       |

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 🙏 Acknowledgments

### 📺 **Tutorial Credits**

This project was inspired by and learned from the excellent tutorial by **[YouTube Channel Name]**:

🎥 **[Modern Todo App Tutorial](https://youtu.be/jdfNnNccDt0?si=jQ86XATHMJLbDGt6)**

Special thanks to the creator for providing such comprehensive and well-structured content that made this project possible. The tutorial covered:

- React Native and Expo setup
- Modern UI/UX design principles
- Real-time database integration with Convex
- Firebase authentication and analytics
- Cross-platform development best practices

### 🛠️ **Technologies & Libraries**

- [Expo](https://expo.dev/) - For the amazing development platform
- [Convex](https://convex.dev/) - For real-time backend functionality
- [Firebase](https://firebase.google.com/) - For authentication and analytics
- [React Native](https://reactnative.dev/) - For cross-platform development
- [Expo Vector Icons](https://icons.expo.fyi/) - For beautiful icons

---

## 📞 Contact

**Your Name** - [@yourusername](https://github.com/yourusername) - your.email@example.com

Project Link: [https://github.com/yourusername/your-repo-name](https://github.com/yourusername/your-repo-name)

---

<div align="center">

**⭐ Star this repository if you found it helpful!**

Made with ❤️ and lots of ☕

</div>
