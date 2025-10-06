# Kabu - Real-Time Multiplayer Card Game

A real-time multiplayer card game built with Firebase, featuring memory and strategy gameplay.

## 🎮 Game Features

- **Real-time multiplayer** - Play with friends online
- **Memory-based gameplay** - Remember card positions and values
- **Strategic elements** - Use special card powers to gain advantages
- **Cross-platform** - Works on desktop and mobile devices
- **Offline support** - Service worker for better performance

## 🚀 Quick Start

1. **Deploy to Netlify**:

   - Drag and drop the project folder to [netlify.com](https://netlify.com)
   - Or connect your GitHub repository for automatic deployments

2. **Configure Firebase**:

   - Create a Firebase project at [console.firebase.google.com](https://console.firebase.google.com)
   - Enable Anonymous Authentication
   - Enable Firestore Database
   - Enable Realtime Database
   - Add your Netlify domain to authorized domains

3. **Update Configuration**:
   - Replace the Firebase configuration in `index.html` with your project settings
   - Deploy the updated code

## 🎯 How to Play

1. **Create or Join** a game using a Game ID
2. **Peek** at your two closest cards at the start
3. **Draw** from the deck or discard pile on your turn
4. **Use special powers** of 7-12 cards or keep them
5. **Call "Kabu"** when you think you have the lowest score
6. **Win** by having the lowest total score when someone reaches 100 points

## 🛠️ Technical Details

- **Frontend**: Vanilla JavaScript, HTML5, CSS3
- **Styling**: Tailwind CSS
- **Backend**: Firebase (Authentication, Firestore, Realtime Database)
- **Deployment**: Netlify
- **PWA**: Service Worker for offline support

## 📁 Project Structure

```
├── index.html          # Main game application
├── sw.js              # Service worker for offline support
├── manifest.json      # PWA manifest
├── netlify.toml       # Netlify configuration
├── _headers           # Security headers
├── _redirects         # URL redirects
└── README.md          # This file
```

## 🔧 Configuration

### Firebase Setup

1. Create a new Firebase project
2. Enable Authentication (Anonymous)
3. Enable Firestore Database
4. Enable Realtime Database
5. Add your domain to authorized domains

### Netlify Configuration

The `netlify.toml` file includes:

- Security headers (CSP, XSS protection)
- Cache control settings
- Redirect rules for SPA routing

## 🚀 Deployment

### Manual Deployment

1. Zip the project folder
2. Upload to Netlify via drag-and-drop

### Git Deployment

1. Push code to GitHub
2. Connect repository to Netlify
3. Enable automatic deployments

## 📱 PWA Features

- **Offline support** via service worker
- **App-like experience** with manifest
- **Responsive design** for all devices
- **Fast loading** with resource caching

## 🔒 Security

- Content Security Policy headers
- XSS protection
- Secure Firebase rules
- HTTPS enforcement

## 🎨 Customization

The game uses Tailwind CSS for styling. Key customization points:

- Color scheme in CSS variables
- Card designs in the card rendering functions
- UI layout in the HTML structure

## 📞 Support

For issues or questions:

1. Check the browser console for error messages
2. Verify Firebase configuration
3. Ensure all required services are enabled
4. Check network connectivity

## 📄 License

MIT License - Feel free to use and modify for your own projects.
