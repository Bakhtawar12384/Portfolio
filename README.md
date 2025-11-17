# Professional Portfolio

A modern, responsive portfolio website showcasing AI projects, digital marketing work, and video content.

## Features

- **Three Main Sections:**
  1. Videos & Social Media Content - Showcase of video ads and social media posts from Elite IT
  2. AI Projects Portfolio - GitHub links and code files for AI projects (Chatbot, NLP IDS, Automations)
  3. Digital Marketing Work - Strategic marketing campaigns and content creation

- **Modern Design:**
  - Clean, professional layout
  - Smooth animations and transitions
  - Fully responsive (mobile, tablet, desktop)
  - Gradient accents and modern UI elements

## How to Use

1. **Open the portfolio:**
   - Simply open `index.html` in your web browser
   - Or host it on any web server

2. **Customize Content:**
   - Replace placeholder video sections with your actual videos
   - Add screenshots of your social media posts
   - Update GitHub/Google Drive links in the AI Projects section
   - Modify text content to match your experience

3. **Add Your Content:**
   - **Videos:** Replace the video placeholder with an `<iframe>` or `<video>` tag
   - **Screenshots:** Replace post placeholders with `<img>` tags pointing to your screenshots
   - **Links:** Update all `href="#"` attributes with your actual GitHub/Google Drive links

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styling
├── script.js       # Interactive features
└── README.md       # This file
```

## Customization Guide

### Adding Videos
Replace the video placeholder div with:
```html
<video controls>
    <source src="your-video.mp4" type="video/mp4">
</video>
```
Or for embedded videos:
```html
<iframe src="your-video-url" frameborder="0" allowfullscreen></iframe>
```

### Adding Screenshots
Replace post placeholders with:
```html
<img src="path-to-screenshot.jpg" alt="Instagram Post">
```

### Updating Links
Find all `href="#"` attributes and replace with your actual URLs:
- GitHub repository links
- Google Drive links
- Project demo links

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- All colors and styling can be customized in `styles.css` using CSS variables
- The portfolio is ready to send to HR - just add your actual content and links
- Make sure all images and videos are optimized for web use

