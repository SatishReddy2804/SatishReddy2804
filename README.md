<div align="center">

# Satish Reddy — Portfolio

**Full-Stack Developer | AI/ML Builder | ServiceNow Developer**

*A single-file portfolio that loads instantly, runs anywhere, and needs no build step.*

<br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Responsive Design](https://img.shields.io/badge/Responsive-Mobile%20First-22D3EE?style=for-the-badge)
<br>
[![GitHub](https://img.shields.io/badge/GitHub-SatishReddy2804-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/SatishReddy2804)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Satish%20Reddy%20K-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/satish-reddy-k-575b63292/)
<!-- LICENSE: change or remove this badge to match the license you choose, and add a LICENSE file to the repo. -->
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<br>

### [DEPLOYED PORTFOLIO] : https://satishreddy-portfolio1206.vercel.app/

</div>

---



## About

This is the personal portfolio of **Karri Veera Venkata Satish Reddy**, a final-year B.Tech Information Technology student at Aditya College of Engineering and Technology.

The site presents full-stack apps, ML decision-support systems, and ServiceNow work in one fast page. Everything lives in a single `index.html`. No frameworks. No build tools. No CDN scripts.

---

## Features

- Dark-first theme with a light-mode toggle that remembers your choice
- Responsive, mobile-first layout with a collapsible menu
- Sticky navigation with active-section highlighting
- Animated hero with a typing effect and a cursor-aware background glow
- Scroll-reveal animations and animated achievement counters
- Project filters: Full-Stack, AI/ML, Frontend, Backend, ServiceNow
- Interactive case-study modals with architecture diagrams
- Contact section with a mail-ready form and one-click copy-email
- In-page resume viewer and download button
- Back-to-top button
- Keyboard-friendly controls with visible focus states
- Reduced-motion support
- Print-friendly, resume-style layout
- SEO description and Open Graph meta tags

---

## Tech Stack

| Layer | Technology |
|:--|:--|
| Markup | HTML5, semantic sections, native `<dialog>` for modals |
| Styling | CSS3, custom properties, Grid, Flexbox, glass-style cards |
| Behavior | Vanilla JavaScript, `IntersectionObserver`, `localStorage` for theme |
| Dependencies | None |
| Build step | None |

---

## Project Highlights

| Project | What it does | Stack | Links |
|:--|:--|:--|:--|
| **MuVora**<br>Multilingual Film Sentiment Intelligence | Analyzes movie reviews for sentiment, aspects, review quality, and translation. | React, TypeScript, Vite, FastAPI, TensorFlow/Keras, Tailwind CSS | [Live](https://jade-pasca-08f89f.netlify.app/) · [Code](https://github.com/SatishReddy2804/MuVora) |
| **Multi-Disease Prediction**<br>Clinical decision support | Predicts heart disease, diabetes, Parkinson's, and liver disease. Adds explainability, uncertainty detection, what-if analysis, and PDF reports. | Python, Django REST Framework, React, PostgreSQL, scikit-learn, XGBoost | [Live](https://multi-disease-prediction-ml.netlify.app/) · [Code](https://github.com/SatishReddy2804/Multi-disease-prediction-using-Machine-Learning) |
| **Job Buddy**<br>AI Job Application Agent | Matches jobs to a resume, analyzes skill gaps, tracks applications on a Kanban board, and generates cover letters and interview prep. | React, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL | [Live](https://job-buddy-ai-live-2026.vercel.app) · [Code](https://github.com/SatishReddy2804/Job-Buddy-AI) |
| **Campus Career Compass**<br>ServiceNow App Engine | No-code app for student career planning, skill-building, and resource access. | ServiceNow, App Engine Studio, Workflow Automation | [Live](https://dev305577.service-now.com/now/appenginestudio/my-apps/0da627484743aa90f606b6bf016d4336) |

---

## Portfolio Sections

| Section | What it covers |
|:--|:--|
| **Hero** | Name, rotating role titles, short pitch, resume button, and social links. |
| **About** | Summary, career objective, current focus, and headline counters. |
| **Skills** | Chips grouped by use: programming, web, backend and data, AI/ML, ServiceNow, core CS. |
| **Projects** | Filterable cards. Each opens a case study with problem, solution, architecture, challenges, and results. |
| **Experience** | ServiceNow internship at Technical Hub Pvt. Ltd. (May–June 2025) and project work. |
| **Education** | B.Tech in Information Technology (2023–2027), plus Class 12 and Class 10. |
| **Achievements** | Certifications and competitive-programming record. |
| **Contact** | Email, copy-email button, mail-ready form, GitHub, and LinkedIn. |

---

## Getting Started

### Option 1: Open directly

```bash
# 1. Clone the repository
git clone https://github.com/SatishReddy2804/portfolio.git
# <!-- Replace "portfolio" with your actual repository name. -->

# 2. Enter the folder
cd portfolio
```

Then open `index.html` in any modern browser.

### Option 2: VS Code Live Server

1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html` and choose **Open with Live Server**.

---

## Customization Guide

Everything is in `index.html`. Search for the text below to jump to each part.

| To change | Where to edit |
|:--|:--|
| **Name and role** | `<title>`, the meta description and Open Graph tags in `<head>`, the `<h1>` in `#home`, and the `words` array in the script (typing effect). |
| **Photo** | The `<img>` inside `#ph`. It is embedded as base64. To use a file, set `src="profile.jpg"`. |
| **About section** | The `#about` block: summary, career objective, "Why hire me", and the `data-n` counters. |
| **Skills** | The `.chip` elements inside `#skills`. |
| **Projects** | The `const P = [...]` array in the script. |
| **GitHub and LinkedIn** | The `.soc` links in `#home`, the buttons in `#contact`, and the footer links. |
| **Resume** | The `RESUME` constant (base64 PDF). To use a file, point the `data-view` and `data-dl` links at `resume.pdf`. |
| **Contact details** | Every `mailto:` link, the email string in the copy-email handler, and the `#form` handler. |
| **Theme colors** | CSS variables at the top of `<style>`. |

**Add a project** by adding an object to `P`:

```js
{
  id: 'my-project',
  cat: 'fullstack frontend',          // filters: fullstack ai frontend backend servicenow
  t: 'Project Name',
  sub: 'One-line subtitle',
  d: 'Short description.',
  tech: ['React', 'Node.js'],
  feat: ['Feature one', 'Feature two'],
  role: 'What you built.',
  gh: 'https://github.com/you/repo',
  live: 'https://your-demo.example'
}
```

**Change theme colors:**

```css
:root {
  --bg: #0a0c12;      /* page background (dark) */
  --bg2: #10131c;     /* alternate background */
  --ac: #22d3ee;      /* accent color */
  --g: linear-gradient(120deg, #3b82f6, #8b5cf6 55%, #22d3ee);  /* gradient */
}
[data-theme=light] {
  --bg: #f6f7fb;
  --bg2: #eceef6;
  --ac: #0e7490;
}
```

**Real form submissions.** The form opens the visitor's mail app. To receive messages directly, send the form to a service such as Formspree or EmailJS.

---

## Deployment

### GitHub Pages

1. Push the repository to GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select `main` and `/ (root)`, then click **Save**.
5. Your site goes live at `https://<username>.github.io/<repository>/`.

### Vercel

1. Sign in at [vercel.com](https://vercel.com) and click **Add New → Project**.
2. Import the repository.
3. Set **Framework Preset** to **Other**. Leave the build command empty.
4. Click **Deploy**.

Or from the terminal:

```bash
npx vercel
```

### Netlify

1. Sign in at [netlify.com](https://netlify.com).
2. Click **Add new site → Import an existing project** and select the repository.
3. Leave the build command empty and set the publish directory to `.`.
4. Click **Deploy**.

Or drag the project folder onto [app.netlify.com/drop](https://app.netlify.com/drop).

---

## Project Structure

```text
portfolio/
├── index.html      # Entire site: HTML, CSS, JS, embedded photo and resume
├── profile.jpg     # Optional: only if you swap out the embedded photo
├── resume.pdf      # Optional: only if you swap out the embedded resume
└── README.md
```



## Contact

| | |
|:--|:--|
| **Email** | [satishreddy2845@gmail.com](mailto:satishreddy2845@gmail.com) |
| **GitHub** | [github.com/SatishReddy2804](https://github.com/SatishReddy2804) |
| **LinkedIn** | [linkedin.com/in/satish-reddy-k-575b63292](https://www.linkedin.com/in/satish-reddy-k-575b63292/) |




<div align="center">

Designed and built by **Karri Veera Venkata Satish Reddy** · HTML, CSS, and JavaScript, nothing else.

</div>
