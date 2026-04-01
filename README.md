# 🚀 Your Award-Winning Portfolio

A cinematic dark-themed developer portfolio built for GitHub Pages.

## 📁 File Structure

```
portfolio/
├── index.html          ← Main page (edit this!)
├── css/
│   └── style.css       ← All styles + theming vars
├── js/
│   └── main.js         ← Cursor, animations, scroll FX
└── assets/             ← Put your photo + resume here
    ├── photo.jpg
    └── resume.pdf
```

## ✏️ How to Customize

### 1. Personal Info (index.html)
Search for and replace:
- `Your Name` → your actual name
- `Your City` → your city
- `hello@yourname.dev` → your email
- `yourusername` → your GitHub/LinkedIn/Twitter handles
- `Y.N` in nav logo → your initials

### 2. Add Your Photo
Place your photo at `assets/photo.jpg`, then in `index.html` replace:
```html
<!-- Replace with: <img src="assets/photo.jpg" alt="Your Name" class="about-photo" /> -->
<div class="about-photo-placeholder">...</div>
```
with:
```html
<img src="assets/photo.jpg" alt="Your Name" class="about-photo" />
```

### 3. Update Projects
Edit the three `.project-card` blocks with your real projects, descriptions, and links.

### 4. Update Experience
Edit the `.timeline-item` blocks with your work history.

### 5. Update Skills
Edit the `.skill-items` blocks with your real stack.

### 6. Add Your Resume
Place your resume at `assets/resume.pdf`.

### 7. Typewriter Roles (js/main.js)
Edit the `roles` array at the top of `main.js`:
```js
const roles = [
  'Full-Stack Developer',
  'Your Role Here',
  ...
];
```

### 8. Theme Color (css/style.css)
Change the accent color at the top:
```css
--accent:  #e8c97e;   /* warm gold — change to your brand color */
--accent2: #c45c3a;   /* secondary accent */
```

## 🌐 Deploy to GitHub Pages

1. Create a repo named `yourusername.github.io`
2. Push all files to the `main` branch
3. Go to **Settings → Pages → Source: main branch / root**
4. Your site will be live at `https://yourusername.github.io` 🎉

Or use any repo + enable Pages under Settings — it'll be at `yourusername.github.io/reponame`.

## ✨ Features
- Custom animated cursor
- Scroll progress bar
- Parallax hero
- Typewriter effect
- Scroll-triggered reveal animations
- 3D tilt on project cards
- Animated number counters
- Fully responsive + mobile menu
- Cinematic dark theme with noise texture
- Zero dependencies — pure HTML/CSS/JS
