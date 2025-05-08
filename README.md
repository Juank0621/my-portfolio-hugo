# Juan Carlos Garzon Portfolio

This is a personal portfolio website built with [Hugo](https://gohugo.io/), styled with [Tailwind CSS](https://tailwindcss.com/), and deployed on [Vercel](https://vercel.com/). It features sections for About, Skills, Experience, and Contact, with a modern, responsive design.

## 🚀 Features
- **Modern design** with animated backgrounds and interactive skill cards
- **Responsive**: Looks great on all devices
- **Contact form** powered by [Formspree](https://formspree.io/)
- **Easy deployment** on Vercel
- **Customizable**: Add your own skills, experience, and projects

## 🛠️ Tech Stack
- [Hugo](https://gohugo.io/) (static site generator)
- [Tailwind CSS](https://tailwindcss.com/)
- [Font Awesome](https://fontawesome.com/) (icons)
- [Formspree](https://formspree.io/) (contact form)
- [Vercel](https://vercel.com/) (hosting)

## 📦 Installation
1. **Clone the repo:**
   ```bash
   git clone https://github.com/tuusuario/tu-repo.git
   cd tu-repo
   ```
2. **Install dependencies:**
   ```bash
   npm install
   ```
3. **Run locally:**
   ```bash
   hugo server
   ```
   The site will be available at [http://localhost:1313](http://localhost:1313)

## 🚀 Deploy on Vercel
1. Push your code to GitHub, GitLab, or Bitbucket.
2. Go to [vercel.com](https://vercel.com/) and import your repo.
3. Use these settings:
   - **Framework Preset:** Other
   - **Build Command:** `hugo --minify`
   - **Output Directory:** `public`
   - **Environment Variable:** `HUGO_VERSION=0.121.2` (or your preferred version)
4. Click **Deploy** and your site will be live!

## ✉️ Contact Form Setup
- The contact form uses [Formspree](https://formspree.io/). Update the `action` attribute in `layouts/partials/contact.html` with your Formspree endpoint.
- Messages will be sent to your Formspree-registered email.

## 📝 Customization
- **Skills, Experience, About:** Edit the markdown files in `content/`.
- **Icons:** Place SVGs in `static/icons/` and update `layouts/partials/skills.html`.
- **Colors & Styles:** Edit `tailwind.config.js` and `assets/css/main.css`.

## 📄 License
This project is open source and available under the [MIT License](LICENSE). 