<div align="center">

# Satish Reddy — Developer Portfolio

**Full-Stack Developer · AI/ML Builder · ServiceNow Developer**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=222)](https://developer.mozilla.org/docs/Web/JavaScript)
![Responsive Design](https://img.shields.io/badge/Responsive-Mobile--first-4C8EDA?style=for-the-badge)
[![GitHub](https://img.shields.io/badge/GitHub-SatishReddy2804-181717?style=for-the-badge&logo=github)](https://github.com/SatishReddy2804)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Satish_Reddy-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/satish-reddy-k-575b63292/)
<!-- Add a license badge only after choosing and adding a LICENSE file. -->

[View the live portfolio](https://satishreddy-portfolio1206.vercel.app/)

</div>

---

## About

I’m **Karri Veera Venkata Satish Reddy**, a final-year B.Tech Information Technology student at Aditya College of Engineering and Technology. I build end-to-end web products, machine-learning applications, and ServiceNow workflows—with a focus on practical features, clear interfaces, and thoughtful implementation.

This repository contains my personal portfolio as a single `index.html` file. It runs directly in a browser with no framework, build step, or required external dependency.

<!-- Update the deployed URL above if the portfolio moves to a new domain. -->

<!-- Add an optimized portfolio screenshot at assets/screenshot.png, then uncomment the image below. -->
<!-- ![Portfolio Screenshot](assets/screenshot.png) -->

## Features

- Dark and light themes with a polished, responsive layout
- Sticky navigation with active-section highlighting and a mobile menu
- Animated hero typing effect and cursor-aware background glow
- Scroll-reveal animations and animated achievement counters
- Project filters for Full-Stack, AI/ML, Frontend, Backend, and ServiceNow
- Interactive project case studies with architecture diagrams
- Contact form that opens the visitor’s email app, plus copy-email-to-clipboard
- Keyboard-visible focus states, accessible navigation, and reduced-motion support
- Print-friendly layout for a resume-style view
- SEO description and Open Graph metadata
- Resume download and preview controls

## Tech Stack

| Technology | Use |
| --- | --- |
| HTML5 | Page structure, content, and metadata |
| CSS3 | Responsive layout, themes, animation, print styles, and visual design |
| Vanilla JavaScript | Interactions, project data, theme controls, navigation, and animations |

No frameworks, package installation, build tools, or external runtime dependencies are needed to open the portfolio.

## Project Highlights

| Project | Overview | Stack | Links |
| --- | --- | --- | --- |
| **MuVora — Multilingual Film Sentiment Intelligence** | Analyzes multilingual movie reviews with sentiment classification, aspect extraction, review-quality checks, and translation. | React, TypeScript, Vite, FastAPI, TensorFlow/Keras, Tailwind CSS | [GitHub](https://github.com/SatishReddy2804/MuVora) · [Live demo](https://jade-pasca-08f89f.netlify.app/) |
| **Multi-Disease Prediction Using Machine Learning** | Clinical decision-support application for heart disease, diabetes, Parkinson’s, and liver disease, with explainability, uncertainty detection, what-if analysis, and PDF reports. | Python, Django REST Framework, React, PostgreSQL, scikit-learn, XGBoost | [GitHub](https://github.com/SatishReddy2804/Multi-disease-prediction-using-Machine-Learning) · [Live demo](https://multi-disease-prediction-ml.netlify.app/) |
| **Job Buddy — AI Job Application Agent** | Supports resume-based job matching, skill-gap analysis, a Kanban application tracker, cover-letter generation, and interview preparation. | React, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL | [GitHub](https://github.com/SatishReddy2804/Job-Buddy-AI) · [Live demo](https://job-buddy-ai-live-2026.vercel.app/) |
| **Campus Career Compass — ServiceNow App Engine** | No-code ServiceNow application for student career planning, skill-building, and resource access. | ServiceNow, App Engine Studio, workflow automation | [Open in ServiceNow](https://dev305577.service-now.com/now/appenginestudio/my-apps/0da627484743aa90f606b6bf016d4336) |

## Portfolio Sections

- **Hero** — Role, introduction, availability, contact links, and resume actions.
- **About** — Background, focus, and selected achievement counters.
- **Skills** — Programming, web, backend and data, AI/ML, ServiceNow, and core CS skills.
- **Projects** — Filterable project cards with links and detailed case-study modals.
- **Experience** — ServiceNow internship and hands-on project work.
- **Education** — B.Tech and previous academic milestones.
- **Achievements** — Certifications and competitive-programming accomplishments.
- **Contact** — Email, social profiles, copy-email action, and an email-app contact form.

## Getting Started

### Run locally

1. Clone the repository:

   ```bash
   git clone https://github.com/SatishReddy2804/SatishReddyPortfolio.git
   cd SatishReddyPortfolio
   ```

   If the repository uses a different GitHub name, replace the URL and directory with the correct values.

2. Open `index.html` in a browser.

   On Windows, you can double-click `index.html`, or run:

   ```powershell
   Start-Process .\index.html
   ```

### Run with VS Code Live Server

1. Open the cloned folder in Visual Studio Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html` and choose **Open with Live Server**.

There is no install or build command.

## Customization Guide

Edit `index.html` to customize the portfolio:

| Content | Where to make the change |
| --- | --- |
| Name and role | Update the hero heading and typing-effect `words` array. Also update the page `<title>`, SEO description, Open Graph metadata, and footer name. |
| Photo | The current portrait is embedded as a data URI in the hero image. To use `profile.jpg`, add the image and replace the `<img>` source with `profile.jpg`. |
| About section | Edit the content in the section with `id="about"`. |
| Skills | Update the skill chips in the section with `id="skills"`. |
| Projects | Edit the `P` array in the JavaScript. Each project entry defines its category, description, technologies, links, and case-study content. |
| GitHub and LinkedIn | Update the profile links in the hero social links, contact section, and footer. |
| Resume download and preview | The current resume is embedded in the JavaScript as base64 data. To use a separate PDF, add `resume.pdf` and update the `RESUME` data and resume link handlers to load that file. |
| Contact details | Update the email addresses in the hero, contact section, form handler, and footer. |
| Theme colors | Change the CSS custom properties in the `:root` and `[data-theme=light]` rules near the top of the `<style>` block. |

<!-- If you add resume.pdf as a separate asset, use a relative link such as [Download my resume](./resume.pdf). -->

## Deployment

This is a static site. Deploy the repository root; no build command or output directory is required.

### GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the branch and `/ (root)` folder, then save.
5. Use the published Pages URL as the live portfolio link.

### Vercel

1. Import the GitHub repository into Vercel.
2. Select the project root as the **Root Directory**.
3. Leave the framework preset as **Other** and leave the build and output directory fields empty.
4. Deploy. Vercel will serve `index.html` as a static site.

### Netlify

1. Import the GitHub repository into Netlify, or deploy the project folder using Netlify Drop.
2. Set the publish directory to the repository root.
3. Leave the build command empty and deploy.

## Project Structure

The current portfolio is self-contained in `index.html`; the portrait and resume data are embedded in that file. The following is a suggested layout if you choose to keep those assets separately:

```text
portfolio/
├── index.html
├── profile.jpg       # Optional: use instead of the embedded portrait
├── resume.pdf        # Optional: use instead of the embedded resume data
└── README.md
```

## Performance and Accessibility

- Serves a single HTML file without a framework, bundler, or required runtime request to a third-party library.
- Uses responsive layouts and CSS media queries for mobile and desktop.
- Provides visible keyboard focus, labeled controls, semantic sections, and status messaging.
- Honors `prefers-reduced-motion` by disabling animation and smooth scrolling.
- Includes print styles for a simpler, resume-friendly presentation.

## Future Enhancements

- Add an optimized portfolio screenshot to the repository.
- Move the embedded portrait and resume into separately maintained assets.
- Add a dedicated contact endpoint for submissions without opening the visitor’s email app.
- Add project-specific screenshots and richer visual previews.

## Contact

- **Email:** [satishreddy2845@gmail.com](mailto:satishreddy2845@gmail.com)
- **GitHub:** [github.com/SatishReddy2804](https://github.com/SatishReddy2804)
- **LinkedIn:** [linkedin.com/in/satish-reddy-k-575b63292](https://www.linkedin.com/in/satish-reddy-k-575b63292/)
- **Portfolio:** [satishreddy-portfolio1206.vercel.app](https://satishreddy-portfolio1206.vercel.app/)

<!-- Add license details and a LICENSE file before publishing a license badge or license claim. -->

---

<div align="center">

Built with HTML, CSS, and JavaScript by **Karri Veera Venkata Satish Reddy**.

</div>
