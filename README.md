# N3X0N Portfolio Website

A personal portfolio site showcasing your YouTube channel, Spotify profile, Gamebanana mods, and work-in-progress projects.

## 📋 Quick Start

This website is built with HTML, CSS, and JavaScript—no build tools needed!

### How to Edit

**To update your links:**

1. Open `index.html` in a text editor (like Notepad, VS Code, or any editor)
2. Find the links that say `YOUR_CHANNEL_HERE` or `YOUR_USERNAME_HERE`
3. Replace them with your actual usernames/links:
   - Line 42: Replace `YOUR_CHANNEL_HERE` with your YouTube channel URL
   - Line 52: Replace `YOUR_SPOTIFY_USERNAME_HERE` with your Spotify username
   - Line 67: Replace `YOUR_GAMEBANANA_USERNAME_HERE` with your Gamebanana username

**To edit project names:**

1. Find the "Work in Progress" section (around line 86)
2. Change "Project Name Here" and "Another WIP Project" to your actual projects
3. Update the descriptions and progress labels

### Customization Guide

#### Change Colors
Edit `styles.css` at the top of the file:
```css
:root {
    --primary-color: #1DB954;    /* Main green/accent color */
    --secondary-color: #191414;  /* Dark background */
    --accent-color: #FF6B6B;     /* WIP section color */
}
