# 💖 Birthday Website for Nishanthini

## Features ✨
- Beautiful gradient animated background
- Floating hearts animation
- Fade-in effects for each section
- Sparkle effects on scroll
- Timeline of your journey together
- Photo gallery section (customizable)
- Promise cards with hover effects
- Fully responsive design
- Music button (ready to add your song)

## How to Deploy to GitHub Pages 🚀

### Step 1: Create a GitHub Repository
1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right, select "New repository"
3. Name it: `nishanthini-birthday` (or any name you like)
4. Make it **Public**
5. Don't initialize with README
6. Click "Create repository"

### Step 2: Upload Your Files
1. Download the `birthday-nishanthini.html` file
2. Rename it to `index.html` (IMPORTANT!)
3. On your GitHub repository page, click "Add file" → "Upload files"
4. Drag and drop the `index.html` file
5. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. In your repository, click "Settings"
2. Scroll down to "Pages" in the left sidebar
3. Under "Source", select "main" branch
4. Click "Save"
5. Wait 1-2 minutes
6. Your site will be live at: `https://[your-username].github.io/nishanthini-birthday/`

## Customization Guide 🎨

### Adding Photos
Replace the photo placeholders in the photo gallery section:
```html
<div class="photo-item">
    <img src="your-photo.jpg" alt="Description" style="width:100%; height:100%; object-fit:cover;">
</div>
```

### Adding Background Music
1. Upload an MP3 file to your repository (e.g., `love-song.mp3`)
2. Uncomment and update the audio code in the script:
```javascript
const audio = new Audio('love-song.mp3');
if (isPlaying) {
    audio.play();
} else {
    audio.pause();
}
```

### Updating Timeline Dates
Edit the timeline section with your actual dates and memories:
```html
<div class="timeline-date">January 15, 2023</div>
<p>Your special memory here</p>
```

### Adding More Sections
Copy any section and paste it before the footer:
```html
<div class="section">
    <h2>Your Custom Title</h2>
    <p>Your content here...</p>
</div>
```

## Tips 💡

1. **Test Locally First**: Open the HTML file in your browser before uploading
2. **Add More Hearts**: Adjust the heart creation interval in JavaScript (currently 500ms)
3. **Change Colors**: Modify the gradient colors in the CSS
4. **Mobile Friendly**: The site is already responsive, but test on your phone
5. **Share the Link**: Once live, you can share the GitHub Pages URL with Nishanthini

## Surprise Ideas 🎁

1. **QR Code**: Create a QR code of the website link and put it in your handwritten letter
2. **Countdown Timer**: Add a countdown to when you'll show her the site
3. **Hidden Messages**: Add Easter eggs that appear on specific clicks
4. **Video Message**: Embed a video message in the gallery section
5. **Interactive Quiz**: Add a fun quiz about your relationship

## Support 💬

If you face any issues:
- Make sure the file is named `index.html` (not `birthday-nishanthini.html`)
- Check if GitHub Pages is enabled in Settings
- Wait a few minutes after uploading for changes to reflect
- Clear your browser cache if updates don't show

---

Made with ❤️ for Nishanthini's Birthday

**Remember**: The best gift is your love and effort. This website combined with your handwritten letter will definitely make her feel special! 💝