# Ava's Portfolio Website

Hi Ava! This README will guide you through setting up and customizing your portfolio website. The website is already styled and ready to go - you just need to add your content!

## 🖼️ Adding Your Content

### Profile Picture
1. Find a good quality photo of yourself
2. Rename it to `profile.jpg`
3. Place it in the `assets/images` folder
   - The image will automatically display on your homepage
   - Recommended size: at least 600x600 pixels
   - Supported formats: JPG, PNG, or WebP

### Resume and Essays
1. Save your resume as a PDF file named `resume.pdf`
2. Save your three essays as PDF files:
   - `essay1.pdf`
   - `essay2.pdf`
   - `essay3.pdf`
3. Place all PDF files in their respective folders:
   - Resume goes in `assets/resume/`
   - Essays go in `assets/essays/`
4. The navigation links will automatically open these files in your browser

## ✏️ Customizing Text

### Homepage Text
Open `index.html` in a text editor and look for these sections:

```html
<p class="intro-text">[Your introduction text goes here...]</p>
<p class="site-description">[This is where you can describe...]</p>
```

1. Replace the text inside the square brackets `[]` with your own content
2. You can remove either section if you don't want to use it
3. Save the file when you're done

## 🌐 Viewing Your Website

### On a Mac
1. Find the folder containing your website files
2. Right-click on `index.html`
3. Select "Open With" → "Safari" (or your preferred browser)
4. Your website will open in the browser

### Making Changes
1. Edit the files using a text editor (like TextEdit or VS Code)
2. Save your changes
3. Refresh the browser to see your updates

## 📤 Publishing to GitHub

1. Create a GitHub account if you don't have one (github.com)
2. Click the "+" button in the top right and select "New repository"
3. Name your repository (e.g., "portfolio")
4. Click "Create repository"
5. On your Mac:
   - Open Finder and go to your website folder
   - Select all files (Command + A)
   - Right-click and select "Compress"
   - This creates a .zip file
6. On GitHub:
   - Click "Add file" → "Upload files"
   - Drag and drop your .zip file
   - Click "Commit changes"
7. Go to your repository settings
   - Scroll down to "GitHub Pages"
   - Under "Source", select "main" branch
   - Click "Save"
8. Your website will be published at: `https://[your-username].github.io/[repository-name]`

## 💡 Tips
- Keep your image files under 1MB for faster loading
- PDF files should be optimized for web viewing (consider reducing file size if needed)
- Test all links after adding new content
- Make sure to save your files with the exact names mentioned above
- If you need to edit the styling, the colors are defined in `style.css`

## 🆘 Need Help?
If you run into any issues:
1. Make sure all files are in the correct folders
2. Check that file names match exactly (including capitalization)
3. Try refreshing your browser after making changes
4. If problems persist, you can contact the person who set this up for you

Happy customizing! 🎉 