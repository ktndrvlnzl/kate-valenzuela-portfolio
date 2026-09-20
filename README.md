# Kate Andrea Valenzuela | Portfolio

My personal portfolio website. I'm a student developer from the Philippines working toward a future in Security Engineering, and this site collects the projects I've built while learning.

**Live site:** https://ktndrvlnzl.github.io/kate-valenzuela-portfolio/

## About the site

The site is a single page with these sections:

- **Hero:** introduction and links to my work and contact details
- **About Me:** who I am, my school, and my goals
- **Skills:** what I'm currently using and what I'm currently learning
- **Things I've Built:** my projects, with links to live demos and code
- **What I Can Help With:** small, realistic things I can help with
- **Where I'm Going:** my learning path toward Security Engineering
- **Career Direction:** Computer Science, then Cybersecurity, then Security Engineering
- **Leadership & Experience:** student leadership, campus journalism, and communication
- **Resume:** a downloadable copy of my resume
- **Contact:** GitHub and email

## Projects featured

| Project | Description | Tech | Link |
| --- | --- | --- | --- |
| Calcifier | A simple calculator built to practice programming logic | HTML, CSS, JavaScript | [Live demo](https://calcifier.netlify.app/) |
| Donezo | A to-do app with local storage, calendar, and dark mode | HTML, CSS, JavaScript | [Live demo](https://ktndrvlnzl.github.io/donezo/) |
| Clock It! | A Pomodoro timer that uses JSON for data storage | Python, Tkinter, JSON | [GitHub](https://github.com/ktndrvlnzl/clock-it-) |
| Lockbox | A password generator and analyzer with separate modules | Python | [GitHub](https://github.com/ktndrvlnzl/lockbox) |

## Design

- Near-black background with light text, and purple used only as a subtle accent
- Palette: `#050404`, `#2E1C2B`, `#4A1942`, `#893168`, `#EAEAEA`
- Fonts: [Bricolage Grotesque](https://fonts.google.com/specimen/Bricolage+Grotesque) for headings and [Geist](https://fonts.google.com/specimen/Geist) for body text, loaded from Google Fonts
- The hero graphic shows the same learning path that appears later in "Where I'm Going"
- The mobile layout is designed separately, with a slide-down menu and full-width buttons

## Built with

- HTML
- CSS
- Vanilla JavaScript (no frameworks or libraries)

The JavaScript handles the mobile menu, scroll reveals, the active navigation link, the scroll-drawn learning path, and the copy-email button.

## Accessibility

- Skip-to-content link
- Visible keyboard focus
- Semantic HTML landmarks and labelled navigation
- Respects `prefers-reduced-motion`
- Text colors chosen for readable contrast on the dark background

## Project structure

```
.
├── index.html                    # the whole site (HTML, CSS, JS)
├── Kate_Valenzuela_Resume.docx   # linked from the Resume section
└── README.md
```

## Run it locally

No build step is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/ktndrvlnzl/kate-valenzuela-portfolio.git
   cd kate-valenzuela-portfolio
   ```
2. Open `index.html` in your browser, or serve the folder:
   ```bash
   python -m http.server 8000
   ```
   Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Push the files to the repository's `main` branch.
2. Go to **Settings > Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. The site will be available at the live link above after a minute or two.

## Customizing

- **Text and links:** edit them directly in `index.html`.
- **Colors:** change the variables in the `:root` block at the top of the `<style>` section.
- **Project previews:** each preview is an inline SVG illustration. To use a real screenshot instead, replace the `.preview` block in a project card with an `<img>`.
- **Resume:** replace `Kate_Valenzuela_Resume.docx` with the new file, keeping the same name (or update the link in the Resume section).

## Contact

- GitHub: [github.com/ktndrvlnzl](https://github.com/ktndrvlnzl)
- Email: kateandreavalenzuela08@gmail.com

&copy; 2026 Kate Andrea Valenzuela
