# 🍽️ Ionic Recipes

A mobile website built in Angular with the Ionic CLI, designed to showcase typical dishes. This application provides an intuitive interface for browsing and discovering recipes in a mobile-friendly format.

## 🌟 Features

- **Recipe Showcase**: Display of typical dishes with detailed information
- **Mobile-First Design**: Optimized for mobile devices with responsive layout
- **Angular Framework**: Built with modern Angular architecture
- **Ionic Components**: Utilizes Ionic's native-like UI components
- **Cross-Platform**: Runs on web browsers and can be built for mobile platforms

## 🛠️ Technologies Used

- **HTML** (46.9%) - Structure and markup
- **TypeScript** (36.4%) - Main application logic
- **SCSS** (13.1%) - Styling and design
- **JavaScript** (1.9%) - Additional functionality
- **Java** (1.7%) - Android platform support
- **Angular** - Frontend framework
- **Ionic CLI** - Mobile app development platform

## 📋 Prerequisites

Make sure you have Node.js and npm installed. You can download and install them from [Node.js](https://nodejs.org/).

## 🔧 Installation Steps

Follow these steps to set up the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/t2ne/ionic-recipes.git
```

### 2. Navigate to Project Directory

```bash
cd ionic-recipes
```

### 3. Install Ionic CLI

```bash
npm install -g @ionic/cli @angular/cli
```

### 4. Install Dependencies

```bash
npm install
```

### 5. Run the Development Server

```bash
ionic serve
```

The application will open in your browser at `http://localhost:8100`.

## 📱 Building for Mobile

### Android

1. Add the Android platform:

   ```bash
   ionic capacitor add android
   ```

2. Build the project:

   ```bash
   ionic capacitor build android
   ```

3. Open in Android Studio:
   ```bash
   ionic capacitor open android
   ```

### iOS (macOS only)

1. Add the iOS platform:

   ```bash
   ionic capacitor add ios
   ```

2. Build the project:

   ```bash
   ionic capacitor build ios
   ```

3. Open in Xcode:
   ```bash
   ionic capacitor open ios
   ```

## 🌐 Supported Browsers

- Chrome
- Firefox
- Safari
- Edge

## 📁 Project Structure

```
ionic-recipes/
├── .vscode/          # VS Code configuration
├── android/          # Android platform files
├── src/              # Source code
│   ├── app/          # Angular application
│   ├── assets/       # Static assets
│   └── environments/ # Environment configurations
├── .browserslistrc   # Browser support configuration
├── .editorconfig     # Editor configuration
├── .eslintrc.json    # ESLint configuration
├── angular.json      # Angular CLI configuration
├── capacitor.config.ts # Capacitor configuration
├── ionic.config.json # Ionic configuration
└── package.json      # Dependencies and scripts
```

## 🚀 Available Scripts

- `ionic serve` - Start development server
- `ionic build` - Build the application
- `ionic test` - Run unit tests
- `ionic capacitor build` - Build for mobile platforms
- `ionic capacitor run` - Run on mobile device/emulator

## 🙋‍♂️ Author

- [@t2ne](https://github.com/t2ne)

## 🎓 Academic Project

This project was developed as part of an academic assignment, demonstrating mobile web development using Angular and Ionic frameworks for creating cross-platform applications.
