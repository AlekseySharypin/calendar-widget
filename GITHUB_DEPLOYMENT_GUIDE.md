# 📁 GitHub Deployment Guide for Beginners

This folder contains all the files you need to upload to GitHub to test your calendar widget online.

## 🚀 Step-by-Step GitHub Deployment

### Step 1: Create a GitHub Account
1. Go to [github.com](https://github.com)
2. Click "Sign up" and create your free account
3. Verify your email address

### Step 2: Create a New Repository
1. Click the "+" icon in the top right corner
2. Select "New repository"
3. Name it: `calendar-widget` (or any name you prefer)
4. Make sure it's set to "Public"
5. Check "Add a README file"
6. Click "Create repository"

### Step 3: Upload Your Files
1. In your new repository, click "uploading an existing file"
2. Drag and drop ALL files from this "GitHub to test" folder:
   - `index.html`
   - `widget.html`
   - `manifest.json`
   - `package.json`
   - `README.md`
   - `assets/` folder (with all icons and screenshots)
3. Write a commit message like "Initial calendar widget upload"
4. Click "Commit changes"

### Step 4: Enable GitHub Pages
1. In your repository, go to "Settings" tab
2. Scroll down to "Pages" section
3. Under "Source", select "Deploy from a branch"
4. Choose "main" branch and "/ (root)" folder
5. Click "Save"
6. Wait 2-3 minutes for deployment

### Step 5: Access Your Live Widget
Your widget will be available at:
```
https://mywildlifestory.github.io/calendar-widget/
```

For direct widget access:
```
https://YOUR-USERNAME.github.io/calendar-widget/widget.html
```

## 📱 Test on iPhone (After GitHub Deployment)

### ⚠️ Important Note About iOS PWAs
iOS treats PWAs (Progressive Web Apps) differently than Android. When you "Add to Home Screen" on iPhone, it creates a web app shortcut, not a native app. This is normal iOS behavior.

### Installation Steps:
1. **Open Safari** on your iPhone (must be Safari, not Chrome)
2. **Go to your site**: `https://mywildlifestory.github.io/calendar-widget/`
3. **Tap the Share button** (⬆️) at the bottom center of Safari
4. **Scroll down** and tap "Add to Home Screen"
5. **Change the name** if you want (default: "Calendar")
6. **Tap "Add"** in the top right

### What You'll Get:
- ✅ **Home Screen Icon** - Your calendar appears as an app icon
- ✅ **Standalone Mode** - Opens without Safari browser bars
- ✅ **Offline Capability** - Works without internet after first load
- ✅ **App-like Experience** - Feels like a native app
- ❌ **Not in App Store** - Won't appear in iPhone widgets or App Store

### iOS Widget Limitation:
**iPhone widgets** (the ones you see when swiping right) can ONLY be added by apps downloaded from the App Store. Web apps cannot appear there - this is an Apple restriction.

### Troubleshooting:
- **No "Add to Home Screen"?** Make sure you're using Safari browser
- **Still looks like website?** The icon might take a minute to appear properly
- **Want it in widgets?** You'd need to submit to App Store (which we prepared files for)

### Alternative Testing:
If the PWA features don't work perfectly, try:
- Clear Safari cache and try again
- Use the direct widget URL: `https://mywildlifestory.github.io/calendar-widget/widget.html`
- Test in Safari's private browsing mode first

## ✅ Files in This Folder

- **index.html** - Landing page for your widget
- **widget.html** - Main calendar widget
- **manifest.json** - PWA configuration for app installation
- **package.json** - Project configuration
- **README.md** - Documentation
- **assets/** - Icons and screenshots for app store
- **GITHUB_DEPLOYMENT_GUIDE.md** - This guide

## 🔧 Important Notes

1. **Free Hosting**: GitHub Pages is completely free
2. **Custom Domain**: You can add your own domain later if needed
3. **Automatic Updates**: When you update files, the site updates automatically
4. **No Server Required**: This is static hosting, perfect for your widget

## 🆘 Need Help?

If you get stuck:
1. Check GitHub's [Pages documentation](https://pages.github.com/)
2. Make sure all files are uploaded correctly
3. Wait a few minutes after enabling Pages
4. Check that your repository is public

## 🎉 What's Next?

After successful deployment:
1. Test the widget on different devices
2. Share the link with friends and family
3. Consider submitting to app stores using the other files in the main project

Good luck with your first GitHub deployment! 🚀
