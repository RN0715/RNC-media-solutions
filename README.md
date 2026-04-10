# RNC-media-solutions
RNC Media Solutions official portfolio website — a premium, responsive showcase of our advertising, brand activations, digital campaigns, and event projects, featuring a modern cinematic UI and dedicated case-study pages.
# RNC Media Solutions Website

Official portfolio website for **RNC Media Solutions**.  
This project presents services, client work, and project case studies with a premium dark UI and responsive experience across desktop and mobile.

## Overview

This is a static frontend website built with:

- HTML
- CSS
- JavaScript (jQuery + vendor plugins from the original Glint base)

The site has been heavily customized for RNC branding, including:

- Premium hero section and motion polish
- Professionalized service, clients, works, and contact sections
- Responsive mobile navigation and layout refinements
- Unified design system across all project detail pages

## Project Structure

```text
glint-master/
├─ index.html
├─ popeyes.html
├─ css/
│  ├─ base.css
│  ├─ vendor.css
│  ├─ main.css
│  └─ project-pages.css
├─ js/
│  ├─ main.js
│  └─ plugins.js
├─ images/
└─ works/
   ├─ glomark.html
   ├─ paymaster.html
   ├─ amazon.html
   ├─ plc.html
   ├─ glooutlet.html
   ├─ echoes.html
   └─ foodlb.html
```

## Run Locally

Since this is a static site, you can open `index.html` directly, but running a local server is recommended.

### Option 1: VS Code Live Server

1. Install **Live Server** extension
2. Right-click `index.html`
3. Click **Open with Live Server**

### Option 2: Python server

```bash
python -m http.server 5500
```

Then open: `http://localhost:5500`

## Deployment (Vercel)

1. Push this project to GitHub.
2. In Vercel, create a new project and import the repo.
3. Use:
   - Framework Preset: `Other`
   - Build Command: *(empty)*
   - Output Directory: *(empty)*
4. Deploy.

If your repo has an extra wrapper folder, set the Vercel **Root Directory** to the folder that contains `index.html`.

## Notes

- Contact form endpoint is `inc/sendEmail.php` (requires PHP backend hosting to function).
- External links and media paths should be reviewed before final production launch.

## License

Customized for RNC Media Solutions from the Glint template base.
