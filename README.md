# my-todo-app
# Todo List PWA

A Progressive Web App (PWA) todo list with calendar deadlines that can be installed on your iPhone like a native app.

## Features

- ‚úÖ Add tasks with optional deadlines
- üìÖ Calendar date picker for due dates
- üî¥ Visual indicators for overdue tasks
- üü° Highlights for tasks due today
- üì± Works offline after first load
- üíæ Automatic data persistence
- üè† Installable on iPhone home screen

## Setup Instructions

### 1. Create App Icons

1. Open `create-icons.html` in your browser
2. Click "Download 192x192 Icon" and save as `icon-192.png`
3. Click "Download 512x512 Icon" and save as `icon-512.png`
4. Place both icon files in the same folder as `index.html`

### 2. Serve the App

The app needs to be served over HTTPS to work as a PWA. Choose one option:

**Option A: Local Development Server**
```bash
# If you have Python 3
python3 -m http.server 8000

# If you have Node.js
npx serve .

# If you have PHP
php -S localhost:8000
```

**Option B: Deploy to a Free Hosting Service**
- GitHub Pages
- Netlify
- Vercel
- Firebase Hosting

### 3. Install on iPhone

1. Open Safari on your iPhone
2. Navigate to your app URL
3. Tap the Share button (square with arrow)
4. Scroll down and tap "Add to Home Screen"
5. Tap "Add" to confirm

## Apple App Store Requirements Met

- ‚úÖ HTTPS serving (required for PWA)
- ‚úÖ Web App Manifest with proper icons
- ‚úÖ Service Worker for offline functionality
- ‚úÖ Responsive design for mobile devices
- ‚úÖ iOS-specific meta tags and styling
- ‚úÖ Touch-friendly interface (44px+ touch targets)
- ‚úÖ Safe area support for newer iPhones
- ‚úÖ No zoom on input focus (prevents iOS zoom)
- ‚úÖ Local data storage (no external dependencies)

## Files Structure

```
todo-app/
‚îú‚îÄ‚îÄ index.html          # Main app file
‚îú‚îÄ‚îÄ manifest.json       # PWA manifest
‚îú‚îÄ‚îÄ sw.js              # Service worker for offline support
‚îú‚îÄ‚îÄ icon-192.png       # App icon (192x192)
‚îú‚îÄ‚îÄ icon-512.png       # App icon (512x512)
‚îú‚îÄ‚îÄ create-icons.html  # Icon generator utility
‚îî‚îÄ‚îÄ README.md          # This file
```

## Privacy & Security

- All data stored locally on device
- No external API calls or tracking
- Works completely offline
- No personal data transmitted

The app meets Apple's PWA requirements and can be installed directly from Safari without App Store submission.
<img width="462" height="642" alt="image" src="https://github.com/user-attachments/assets/26c51af4-251b-4887-afa4-3518b32b4778" />

