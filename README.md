# Anshul Deep Bajpai — Portfolio

A modern, responsive, single-file personal portfolio website for **Anshul Deep Bajpai**, an AI & Machine Learning undergraduate and aspiring AI Engineer.

The portfolio showcases my skills, experience, projects, certifications, education, and contact information through a clean, accessible, and responsive interface.

## 🌐 Live Portfolio

**Portfolio:** `https://anshul-deep-bajpai-portfolio.vercel.app`

## ✨ Features

* 🌙 **Dark / Light Mode**

  * Theme toggle available in the header
  * Theme preference saved using `localStorage`
  * Automatically detects the visitor's OS theme preference on first visit

* 📊 **Project Statistics**

  * 46K+ NAV records
  * 32.8K investor transactions
  * 40 fund schemes
  * 5 shipped projects
  * 6 certifications

* 📱 **Fully Responsive**

  * Desktop
  * Tablet
  * Mobile
  * Responsive navigation drawer
  * Single-column layouts on smaller screens

* ♿ **Accessible**

  * Semantic HTML5 landmarks
  * Skip-to-content link
  * Visible keyboard focus states
  * ARIA attributes for interactive elements
  * Reduced-motion support

* 🎬 **Scroll Reveal Animations**

  * Powered by the native `IntersectionObserver` API
  * Automatically disabled when the visitor prefers reduced motion

* ⚡ **Zero Runtime Dependencies**

  * No React
  * No Bootstrap
  * No Tailwind
  * No build tools
  * No JavaScript frameworks

* 🎨 **Modern UI**

  * CSS custom properties
  * CSS Grid
  * Flexbox
  * Responsive design
  * Modern typography

## 📂 Project Structure

```text
Anshul-Deep-Bajpai-Portfolio/
│
├── index.html
├── README.md
└── Anshul_Deep_Bajpai_Resume.pdf
```

### `index.html`

Contains the complete portfolio:

* HTML structure
* CSS styling
* Responsive layouts
* Theme system
* JavaScript interactions
* Scroll animations
* Navigation
* Portfolio content

### `Anshul_Deep_Bajpai_Resume.pdf`

Downloadable résumé linked from the portfolio's Hero section and Footer.

### `README.md`

Project documentation and setup instructions.

## 🧑‍💻 Portfolio Sections

The website includes:

1. **Hero**
2. **About**
3. **Skills**
4. **Experience**
5. **Projects**
6. **Certifications**
7. **Education**
8. **Contact**

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* CSS Grid
* CSS Flexbox
* CSS Custom Properties

### Fonts

* Space Grotesk
* Inter
* IBM Plex Mono

Fonts are loaded from Google Fonts.

### Browser APIs

* `localStorage`
* `IntersectionObserver`
* `matchMedia`
* `prefers-color-scheme`
* `prefers-reduced-motion`

## 🚀 Running Locally

No installation or build process is required.

### Option 1 — Open Directly

Simply double-click:

```text
index.html
```

The portfolio will open in your default browser.

### Option 2 — Run a Local Server

Using Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

On Windows, you can also use:

```bash
python -m http.server 8000
```

## 📄 Résumé Setup

Make sure the résumé PDF is located in the same directory as `index.html`:

```text
Anshul-Deep-Bajpai-Portfolio/
│
├── index.html
└── Anshul_Deep_Bajpai_Resume.pdf
```

The résumé link uses a relative path:

```html
href="Anshul_Deep_Bajpai_Resume.pdf"
```

If the résumé is moved to another location, update the corresponding links in `index.html`.

## 🌍 Deployment

Because this is a static website, it can be deployed on almost any static hosting platform.

### Vercel

1. Upload the project to GitHub.
2. Import the repository into Vercel.
3. Deploy the project.
4. No build command is required.

### Netlify

The project can be deployed using:

* Git repository
* Netlify dashboard
* Drag-and-drop deployment

### GitHub Pages

1. Push the project to GitHub.
2. Open repository **Settings**.
3. Go to **Pages**.
4. Select the main branch.
5. Save the configuration.

## 🎨 Customization

Most customization can be done directly inside `index.html`.

| Component            | Location                      |
| -------------------- | ----------------------------- |
| Light theme colors   | `:root` CSS variables         |
| Dark theme colors    | `html[data-theme="dark"]`     |
| Fonts                | `<link>` elements in `<head>` |
| About section        | `#about`                      |
| Skills               | `#skills`                     |
| Experience           | `#experience`                 |
| Projects             | `#projects`                   |
| Certifications       | `#certifications`             |
| Education            | `#education`                  |
| Contact information  | `#contact`                    |
| Portfolio statistics | Metrics section below Hero    |

## 📊 Portfolio Metrics

The statistics section highlights selected project and career metrics:

| Metric                | Value |
| --------------------- | ----: |
| NAV Records           |  46K+ |
| Investor Transactions | 32.8K |
| Fund Schemes          |    40 |
| Shipped Projects      |     5 |
| Certifications        |     6 |

## 📬 Contact

**Email:**
`anshuldeepbajpai@gmail.com`

**LinkedIn:**
`in/anshul-deep-bajpai`

**GitHub:**
`anshuldeepbajpai-dhoni`

## 📌 Featured Work

The portfolio highlights projects involving areas such as:

* Artificial Intelligence
* Machine Learning
* Data Analytics
* Financial Analytics
* Computer Vision
* Natural Language Processing
* Python
* Full-stack AI applications

## 🔐 Accessibility & Performance

The portfolio is designed with accessibility and performance in mind.

### Accessibility

* Semantic HTML5
* Keyboard navigation
* Focus indicators
* ARIA labels
* Skip navigation
* Reduced-motion support
* Responsive layouts

### Performance

* No frontend framework
* No build step
* Minimal JavaScript
* Inline CSS and JavaScript
* Native browser APIs
* Minimal external requests

## 📜 License

This project is a personal portfolio website created by **Anshul Deep Bajpai**.

The source structure and implementation may be referenced for learning purposes, but personal information, résumé content, project descriptions, and branding should not be reused without permission.

---

## 👨‍💻 Author

### Anshul Deep Bajpai

**B.Tech CSE — AI & Machine Learning**

Aspiring **AI Engineer | Machine Learning Engineer | Data Analyst**

📧 `anshuldeepbajpai@gmail.com`

🔗 LinkedIn: `in/anshul-deep-bajpai`

💻 GitHub: `anshuldeepbajpai-dhoni`
