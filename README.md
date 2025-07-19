# Personal Calendar Widget

A beautiful, responsive calendar widget that displays your personal photos with automatic holiday detection and note-taking capabilities.

## 🌟 Features

- **Personal Photo Backgrounds**: Display your own photos for each month
- **Holiday Detection**: Automatically detects and displays holidays for your country
- **Multi-language Support**: Supports 10 languages with automatic detection
- **Note Taking**: Add notes to any date with reminder notifications
- **Responsive Design**: Works perfectly on desktop and mobile devices
- **PWA Ready**: Can be installed as a standalone app
- **Offline Support**: Works without internet connection

## 🌍 Supported Languages

- English
- Spanish (Español)
- French (Français)
- German (Deutsch)
- Italian (Italiano)
- Portuguese (Português)
- Russian (Русский)
- Chinese (中文)
- Japanese (日本語)
- Arabic (العربية)

## 🎉 Supported Countries for Holidays

- United States
- United Kingdom
- Canada
- Germany
- France
- Spain
- Italy
- Russia
- Japan
- China

## 📱 Installation

### Option 1: Direct Installation
1. Open `widget.html` in your web browser
2. Click the install button when prompted (PWA installation)
3. The widget will be added to your home screen/applications

### Option 2: Web Server
1. Serve the files using any web server
2. Navigate to the URL in your browser
3. Install as PWA for best experience

### Option 3: Development
```bash
npm install
npm start
```

## 🖼️ Customizing Photos

### Using Your Own Server Photos
1. Upload your photos to a web server
2. Edit the `monthlyPhotos` object in `widget.html`
3. Replace the URLs with your own photo URLs

### Using Local Photos
1. Place your photos in the `photos/` directory
2. Name them: `january.jpg`, `february.jpg`, etc.
3. Run the setup script: `./setup.sh`

## 📝 Photo Requirements

- **Format**: JPG, PNG, or WebP
- **Aspect Ratio**: 1:1 (square) recommended
- **Resolution**: 800x800px minimum
- **File Size**: Under 2MB per photo for best performance

## 🎨 Customization

The widget is fully customizable through CSS variables and JavaScript configuration:

- Colors and themes
- Photo sources
- Holiday data
- Language preferences
- Animation settings

## 🔧 Technical Requirements

- Modern web browser with JavaScript enabled
- Internet connection for holiday detection (optional)
- HTTPS for PWA installation (recommended)

## 📱 Mobile Support

The widget is fully responsive and optimized for:
- iOS Safari
- Android Chrome
- Desktop browsers
- Tablet devices

## 🛡️ Privacy

- All notes are stored locally in your browser
- No personal data is transmitted to external servers
- Holiday data is fetched from public APIs only
- Your photos remain on your chosen server

## 📄 License

MIT License - feel free to modify and distribute

## 🆘 Support

For issues or feature requests, please contact support or create an issue in the repository.

## 🔄 Updates

The widget automatically checks for updates and can be updated through your browser's PWA management.

---

Made with ❤️ for personal organization and beautiful calendar experiences.

## Installation

### For Desktop (Browser/PWA)
1. Open `widget.html` in your web browser
2. For Chrome/Edge: Click the install button in the address bar to install as a PWA
3. For standalone use: Bookmark the page or save as desktop shortcut

### For Mobile Devices
1. Open `widget.html` in your mobile browser
2. Add to home screen (iOS Safari: Share → Add to Home Screen, Android Chrome: Menu → Add to Home Screen)

### For Widget Platforms
- **Windows**: Use as a web widget in widgets panel
- **macOS**: Use with Dashboard or third-party widget apps
- **Android**: Use with widget apps that support web widgets
- **iOS**: Use with Shortcuts app or widget apps

## Customization

### Adding Your Own Photos

Replace the photo URLs in the `monthlyPhotos` object in `widget.html`:

```javascript
const monthlyPhotos = {
    0: 'path/to/your/january-photo.jpg',    // January
    1: 'path/to/your/february-photo.jpg',   // February
    2: 'path/to/your/march-photo.jpg',      // March
    // ... continue for all 12 months
};
```

### Photo Requirements
- **Aspect Ratio**: Square (1:1) recommended for best results
- **Resolution**: Minimum 800x800px, 1200x1200px recommended
- **Format**: JPG, PNG, or WebP
- **Size**: Keep under 500KB per image for fast loading

### Local Photo Setup
1. Create a `photos` folder in the same directory as `widget.html`
2. Add your 12 photos named: `01-january.jpg`, `02-february.jpg`, etc.
3. Update the photo paths in the script:
   ```javascript
   const monthlyPhotos = {
       0: './photos/01-january.jpg',
       1: './photos/02-february.jpg',
       // ... etc
   };
   ```

## File Structure
```
CalendarWidget/
├── widget.html          # Main widget file
├── manifest.json        # PWA manifest for installation
├── README.md            # This file
└── photos/              # Your personal photos (create this folder)
    ├── 01-january.jpg
    ├── 02-february.jpg
    └── ... (12 photos total)
```

## Browser Compatibility
- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 11+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## License
Free to use and modify for personal use.

## Support
For issues or questions, check that:
1. All photo URLs are accessible
2. Photos are in square (1:1) aspect ratio
3. Browser supports CSS Grid and modern JavaScript features

Enjoy your personalized calendar widget! 📅✨
