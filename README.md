# 🎯 AI/ML Portfolio - Pramod Kumar Marri

A modern, responsive portfolio website showcasing my journey as an AI/ML Engineer, featuring projects in LLM integration, RAG systems, and deep learning applications.

[![Live Demo](https://img.shields.io/badge/demo-online-brightgreen)](https://pramodkumarmarri.github.io/ai-ml-portfolio)
[![GitHub](https://img.shields.io/badge/GitHub-pramod--27-blue)](https://github.com/pramod-27)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0077B5)](https://linkedin.com/in/pramodkumarmarri)

---

## 🌟 Features

- **Responsive Design** - Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional layout with smooth animations
- **Project Showcase** - Detailed presentation of AI/ML projects with tech stacks
- **Interactive Elements** - Smooth scrolling, hover effects, and dynamic content
- **Contact Integration** - Direct links to email, phone, and social profiles
- **Resume Download** - One-click access to detailed CV

---

## 🚀 Quick Start

### Clone Repository
```bash
git clone https://github.com/pramod-27/pramod_ai-ml-portfolio
cd ai-ml-portfolio
```

### Local Development

**Option 1: Using Live Server (Recommended)**
```bash
# Install Live Server globally
npm install -g live-server

# Run the server
live-server
```
Access at: `http://127.0.0.1:8080`

**Option 2: Direct Browser Access**
- Simply open `index.html` in your preferred browser
- No server required for basic functionality

**Option 3: Python Simple Server**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```
Access at: `http://localhost:8000`

---

## 📁 Project Structure

```
ai-ml-portfolio/
├── index.html                      # Main portfolio page
├── README.md                       # Documentation (this file)
├── .gitignore                      # Git exclusions
│
├── assets/
│   ├── css/
│   │   ├── styles.css              # Custom styles
│   │   └── swiper-bundle.min.css   # Slider library styles
│   │
│   ├── js/
│   │   ├── main.js                 # Main JavaScript logic
│   │   ├── swiper-bundle.min.js    # Slider functionality
│   │   └── mixitup.min.js          # Filter/sort functionality
│   │
│   ├── img/
│   │   ├── profile.png             # Profile photo
│   │   ├── about.jpg               # About section image
│   │   ├── work1.jpg               # Project screenshots
│   │   ├── work2.jpg
│   │   ├── work3.jpg
│   │   └── testimonial*.jpg        # Testimonial images
│   │
│   ├── pdf/
│   │   └── Resume_Pramod_Kumar_Marri.pdf
│   │
│   └── favicons/
│       ├── favicon.ico
│       └── favicon-32x32.png
```

---

## 🎨 Customization Guide

### 1. Personal Information
Edit `index.html`:
```html
<!-- Update name, title, and description -->
<h1 class="home__title">Pramod Kumar Marri</h1>
<h3 class="home__subtitle">AI/ML Engineer</h3>
<p class="home__description">Your bio here...</p>
```

### 2. Profile Images
Replace images in `assets/img/`:
- `profile.png` - Your professional headshot (recommended: 400x400px)
- `about.jpg` - About section image
- `work*.jpg` - Project screenshots/demos

### 3. Projects
Update project details:
```html
<!-- In the projects section -->
<div class="work__card">
    <img src="assets/img/work1.jpg" alt="Project Name">
    <h3>Your Project Title</h3>
    <span>Tech Stack</span>
    <a href="your-project-link">View Demo</a>
</div>
```

### 4. Resume
Replace `assets/pdf/Resume_Pramod_Kumar_Marri.pdf` with your updated resume

### 5. Contact Links
Update social media and contact links:
```html
<a href="https://github.com/your-username">GitHub</a>
<a href="https://linkedin.com/in/your-profile">LinkedIn</a>
<a href="mailto:your-email@gmail.com">Email</a>
```

### 6. Colors & Styling
Modify `assets/css/styles.css`:
```css
:root {
    --first-color: #3B82F6;        /* Primary blue */
    --second-color: #8B5CF6;       /* Secondary purple */
    --text-color: #1F2937;         /* Text color */
}
```

---

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Push to GitHub:**
```bash
git add .
git commit -m "Initial portfolio setup"
git push origin main
```

2. **Enable GitHub Pages:**
   - Go to Repository Settings
   - Navigate to "Pages" section
   - Source: Select `main` branch
   - Click Save

3. **Access Your Site:**
   - URL: `https://your-username.github.io/repository-name`
   - Example: `https://pramodkumarmarri.github.io/ai-ml-portfolio`

### Alternative Hosting Options

**Netlify:**
1. Drag & drop your project folder to [Netlify](https://app.netlify.com/)
2. Instant deployment with custom domain support

**Vercel:**
```bash
npm install -g vercel
vercel
```

**Firebase Hosting:**
```bash
firebase init hosting
firebase deploy
```

---

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox/Grid
- **JavaScript** - Interactive functionality
- **Swiper.js** - Touch slider library
- **MixItUp** - Filtering and sorting
- **Boxicons** - Icon library
- **ScrollReveal** - Scroll animations

---

## 📊 Portfolio Sections

### 🏠 Home
- Professional introduction
- Call-to-action buttons
- Social media links

### 👤 About
- Educational background
- Statistics (CGPA, Projects, Experience)
- Certifications
- Contact information

### 💼 Experience
- Internship details
- Key achievements
- Technologies used
- Timeline format

### 🚀 Projects
- Featured AI/ML projects
- Tech stack badges
- Project descriptions
- Live demo links

### 🎯 Skills
- Programming languages
- AI/ML frameworks
- Databases
- Tools & platforms
- Categorized display

### 📧 Contact
- Email integration
- Phone contact
- Social media links
- Contact form (optional)

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📝 License

This project is **MIT** licensed - feel free to use it for your own portfolio!

---

## 📞 Contact & Support

**Pramod Kumar Marri**
- 📧 Email: [pramodkumarmarri711@gmail.com](mailto:pramodkumarmarri711@gmail.com)
- 💼 LinkedIn: [linkedin.com/in/pramodkumarmarri](https://www.linkedin.com/in/pramod-kumar-marri-a1936225a/)
- 🐙 GitHub: [github.com/pramod-27](https://github.com/pramod-27)
- 📱 Phone: +91-7842322116
- 🌍 Location: Vijayawada, India

---

## 🙏 Acknowledgments

- Design inspiration from modern portfolio templates
- Icons by [Boxicons](https://boxicons.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)
- Animations powered by [ScrollReveal](https://scrollrevealjs.org/)

---

## 📈 Future Enhancements

- [ ] Add dark mode toggle
- [ ] Integrate blog section
- [ ] Add project filtering by technology
- [ ] Implement contact form backend
- [ ] Add loading animations
- [ ] SEO optimization
- [ ] Analytics integration
- [ ] Multi-language support

---

<div align="center">

### ⭐ If you found this helpful, please consider giving it a star!

**© 2025 Pramod Kumar Marri | Built with ❤️ for AI Innovation**

[![Download Resume](https://img.shields.io/badge/Download-Resume-blue?style=for-the-badge)](./assets/pdf/Resume_Pramod_Kumar_Marri.pdf)

</div>