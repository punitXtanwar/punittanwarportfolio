# Punit Tanwar - Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript.

## 📁 Project Structure

```
portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Stylesheet
├── script.js           # JavaScript file
├── README.md           # This file
│
└── assets/             # Image folder (you need to create this)
    ├── profile.jpg     # Your profile photo
    ├── certificate.jpg # Your certificate image
    ├── netacad.jpg     # NetAcad certificate (optional)
    ├── yuvaai.jpg      # YuvaAI certificate (optional)
    └── resume.pdf      # Your resume (optional)
```

## 🚀 How to Use

### Step 1: Create the Folder Structure
1. Create a new folder named `portfolio`
2. Inside it, create a subfolder named `assets`

### Step 2: Add Your Images
Copy your images into the `assets` folder with these exact names:

| File Name | Description | Used In |
|-----------|-------------|---------|
| `profile.jpg` | Your profile photo (the sunset bike ride photo) | Home section, Gallery |
| `certificate.jpg` | Your Coursera/certificate image | Certificates section, Gallery |
| `netacad.jpg` | Cisco NetAcad certificate (optional) | Certificates section |
| `yuvaai.jpg` | YuvaAI certificate (optional) | Certificates section |
| `resume.pdf` | Your resume PDF (optional) | Download button |

**Important:** If your images have different file extensions (like `.png` or `.jpeg`), either:
- Rename them to match the names above, OR
- Update the file paths in `index.html`

### Step 3: Update Contact Information
Open `index.html` and update the following placeholders:

1. **Email**: Find `punit.tanwar@email.com` and replace with your actual email
2. **Phone**: Find `+91 98765 43210` and replace with your actual phone number
3. **Social Links**: Update the `#` in social media links with your actual profile URLs

### Step 4: Open in Browser
Simply double-click `index.html` to open it in your web browser.

## 🎨 Features

- ✅ **Responsive Design** - Works on mobile, tablet, and desktop
- ✅ **Smooth Scrolling Navigation**
- ✅ **Mobile Hamburger Menu**
- ✅ **Image Lightbox** - Click images to view in full size
- ✅ **Scroll Animations** - Elements fade in as you scroll
- ✅ **Hover Effects** - Interactive cards and buttons
- ✅ **Scroll to Top Button**
- ✅ **Professional Color Scheme**
- ✅ **Font Awesome Icons**
- ✅ **Google Fonts (Poppins)**

## 📱 Sections Included

1. **Home** - Name, introduction, profile photo, social links
2. **About Me** - Education, interests, goals
3. **Education & Skills** - Timeline, technical skills, hobbies
4. **Certificates** - Coursera, NetAcad, YuvaAI
5. **Projects** - AI4A, Design Thinking, Portfolio Website
6. **Gallery** - Photo gallery with lightbox
7. **Contact** - Email, phone, location, social media

## 🛠️ Technologies Used

- HTML5 (Semantic markup)
- CSS3 (Flexbox, Grid, Animations)
- JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts

## 📝 Customization

### Changing Colors
Edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #4a6fa5;    /* Main blue color */
    --secondary-color: #f4a261;   /* Orange accent */
    --accent-color: #2a9d8f;      /* Teal accent */
}
```

### Adding More Projects
Copy a project card in `index.html` and modify the content:

```html
<div class="project-card">
    <div class="project-image">
        <div class="project-icon">
            <i class="fas fa-your-icon"></i>
        </div>
    </div>
    <div class="project-content">
        <span class="project-tag">Category</span>
        <h3>Project Name</h3>
        <p>Project description...</p>
        <div class="project-links">
            <a href="#" class="project-link">View Project</a>
        </div>
    </div>
</div>
```

## 🌐 Deployment

To deploy on GitHub Pages:

1. Create a new repository on GitHub
2. Upload all files (index.html, style.css, script.js, assets folder)
3. Go to Settings > Pages
4. Select source as "main branch"
5. Your site will be live at `https://yourusername.github.io/repository-name`

## 📄 License

This project is created for educational purposes as part of the MIT Vishwaprayag University assignment.

---

**Created by:** Punit Tanwar  
**Institution:** MIT Vishwaprayag University  
**Course:** BBA (Bachelors of Business Administration)
