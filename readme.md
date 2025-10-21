# Kaveesha Mallawaarachchi - Portfolio Website

A modern, minimalist portfolio website featuring a dark navy theme with teal accents, showcasing skills in Python development, Telegram bots, web development, and mobile apps.

## 🚀 Features

- **Minimalist Dark Theme**: Professional dark navy background (#0a192f) with teal accent color (#64ffda)
- **Large Bold Typography**: Eye-catching Poppins font with clean hierarchy
- **Scroll Animations**: Smooth fade-in effects as you scroll through sections
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **GitHub Pages Ready**: Pure HTML, CSS, and JavaScript - no build process required
- **Professional Sections**: Hero, About with stats, Skills, Projects with tech tags, Contact grid
- **SEO Optimized**: Proper meta tags and semantic HTML structure

## 📁 File Structure

```
portfolio/
├── index.html      # Main HTML structure
├── style.css       # Minimalist dark theme with animations
├── script.js       # Hamburger menu, smooth scrolling & scroll animations
├── profile.svg     # Placeholder profile image (replace with your photo)
├── .gitignore      # Git ignore file
└── README.md       # This file
```

## 🎨 Design Features

### Color Palette
- **Primary Background**: #0a192f (Dark Navy)
- **Secondary Background**: #112240 (Navy Blue)
- **Accent Color**: #64ffda (Teal/Cyan)
- **Text Primary**: #e6f1ff (Light Blue)
- **Text Secondary**: #8892b0 (Slate)

### Typography
- **Font Family**: Poppins (Google Fonts)
- **Hero Name**: 5rem (responsive, clamps down to 3rem on mobile)
- **Section Titles**: 2.5rem with numbered prefixes

### Key Components
1. **Fixed Navigation**: Semi-transparent navbar with scroll effect
2. **Hero Section**: Large typography with animated scroll indicator
3. **Numbered Sections**: Professional section headers with decorative lines
4. **Stats Display**: Showcase achievements with large numbers
5. **Skill Cards**: Three-column grid with hover effects and icons
6. **Project Cards**: Numbered cards with tech tags and GitHub links
7. **Contact Grid**: Icon-based contact cards for all platforms
8. **Footer**: Social links with hover animations

## 🛠️ Customization

### Replace Profile Image
You can add your own photo by:
1. Adding your image to the project folder (e.g., `profile.jpg`)
2. Updating the `src` attribute in the hero section (currently using `profile.svg` as placeholder)

### Update Personal Information
Edit `index.html` to update:
- **Name**: Line 38 (hero name)
- **Bio**: Lines 52-54 (about section)
- **Skills**: Lines 62-93 (skill categories)
- **Projects**: Lines 107-185 (project cards)
- **Contact**: Lines 213-248 (social links)

### Modify Colors
Edit CSS variables in `style.css` (lines 1-10):
```css
:root {
    --bg-primary: #0a192f;
    --accent-primary: #64ffda;
    /* etc. */
}
```

### Update Stats
Change the statistics in the About section (around line 75 in `index.html`):
- Number of projects
- Technologies mastered
- Other achievements

## 🌐 Deploy to GitHub Pages

1. **Create a GitHub Repository**
   ```bash
   git init
   git add .
   git commit -m "Initial commit - Portfolio website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Under "Source", select `main` branch
   - Click Save
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

3. **Custom Domain (Optional)**
   - Add a `CNAME` file with your domain name
   - Configure DNS settings with your domain provider

## 🖥️ Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python3 -m http.server 5000

# Python 2
python -m SimpleHTTPServer 5000

# Node.js (if you have npx)
npx serve

# PHP
php -S localhost:5000
```

Then visit `http://localhost:5000`

## ✨ Animations & Interactions

- **Scroll Animations**: Sections fade in as you scroll using Intersection Observer API
- **Smooth Scrolling**: Click navigation links for smooth page transitions
- **Hover Effects**: Cards lift and change border color on hover
- **Mobile Menu**: Animated hamburger menu with smooth toggle
- **Navbar Effect**: Navbar gains shadow effect on scroll

## 📱 Browser Compatibility

- ✅ Chrome/Edge (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Opera (latest)
- ⚠️ IE11 (basic support, limited animations)

## 🎯 Performance

- **Lightweight**: No heavy frameworks or libraries
- **Fast Loading**: Minimal HTTP requests
- **Optimized Animations**: CSS transforms and opacity for smooth 60fps
- **Efficient JS**: Single Intersection Observer for all scroll animations

## 🤝 Connect

- 📧 Email: hello@kaveeshainduwara.lk
- 💼 LinkedIn: [Kaveesha Mallawaarachchi](https://linkedin.com/in/kaveesha-induwara)
- 🐙 GitHub: [@Monster-ZeroX](https://github.com/Monster-ZeroX)
- ✈️ Telegram: [@Monster_ZeroX](https://t.me/Monster_ZeroX)
- 📸 Instagram: [@kaveesha_induwara](https://instagram.com/kaveesha_induwara)

## 📄 License

Feel free to use this template for your own portfolio. Attribution appreciated but not required.

---

**Built with passion using HTML, CSS & JavaScript** 🚀
