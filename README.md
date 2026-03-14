<div align="center">

# 💍 Premium Marriage Biodata Template

A beautiful, modern, and fully responsive Marriage Biodata HTML/CSS template featuring a luxurious glassmorphism design, interactive animations, and automatic English-to-Tamil language translation.  

[![HTML5 Badge](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#) [![CSS3 Badge](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#) [![JavaScript Badge](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)

### 🌟 [View Live Demo Here](https://subramanian162.github.io/subu_marriage_biodata/) 🌟

---

</div>

## ✨ Key Features

- **💎 Premium Glassmorphism UI**: Uses frosted-glass cards floating over a soft gradient, animated background.
- **📱 100% Mobile Responsive**: Seamlessly adapts to any screen size. Lists and grids stack gracefully on mobile phones.
- **🔄 Instant Bilingual Swap**: Includes a custom-built, zero-dependency engine to switch the entire page between English and Tamil instantly.
- **📸 Smart Image Export**: Built-in functionality using `html2canvas` to capture the entire biodata page perfectly as a PNG image for sharing via WhatsApp or Email. 
- **⚡ Super Fast**: Extremely lightweight requiring zero backend or complex frameworks. Just drop the files onto any web server.
- **🎨 Modern Typography**: Uses `Playfair Display` for elegant serif headings and `Inter` for highly readable body text.

## 🚀 Live Demo & Deployment

This application can be hosted entirely for free using GitHub pages.

**To deploy your own copy:**
1. Fork or download this repository.
2. Go to your repository settings -> **Pages**.
3. Select the `main` branch as your source.
4. GitHub will give you a public URL (e.g. `https://yourusername.github.io/subu_marriage_biodata/`) where anyone can view your Biodata.

## 🛠️ Customization Guide

Modifying the template with your own details is incredibly easy:

### 1. Update Profile Details
Open the `data.js` file in any text editor. You will see a `profileData` object containing all of the text content used on the page. Simply replace the placeholder values inside the quotes (like `"Aditya Sharma"`) with your own information. The web page will automatically inject these values into the Biodata layout.

### 2. Update Tamil Translations
If you add or alter the text values in `data.js`, remember to update the corresponding Tamil translation!  
Scroll towards the bottom of `index.html` and look for the `enToTa` object in the JavaScript block:
```javascript
const enToTa = {
    // English Text : "Tamil Translation"
    "Your Name": "உங்கள் பெயர்",
    // Add your new strings here!
}
```

### 3. Change Theme Colors
You can change the entire color scheme instantly by altering the CSS variables at the very top of `styles.css`:
```css
:root {
    --primary-bg: #fffbf9;
    --text-primary: #2d2a26;
    --accent-color: #d4af37; /* The Metallic Gold Accent */
    
    /* Background Gradients */
    --gradient-1: #ffd1d1;
    --gradient-2: #ffe6cf;
    --gradient-3: #f5d1ff;
}
```

## 📦 Dependencies

This repository intentionally avoids complex build tools (like Webpack/NPM), so it runs directly in the browser! It imports a few external libraries via CDN:
- **[Remix Icons](https://remixicon.com/)**: For the clean UI icons.
- **[Google Fonts](https://fonts.google.com/)**: For the beautiful typography choices.
- **[html2canvas](https://html2canvas.hertzen.com/)**: For the Image export functionality.

## 📄 License

This project is free to use, distribute, and modify for personal and non-commercial purposes! 

<div align="center">
<i>Created with sincerity and hope.</i> 💖
</div>
