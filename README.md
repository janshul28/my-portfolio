# my-portfolio
A modern, fully responsive personal portfolio website built with pure HTML, CSS, and Vanilla JavaScript — zero frameworks, zero dependencies, zero build steps. Just one file and it works.

🌐 Live Demo

https://janshul28.github.io/portfolio


📸 Preview
Hero SectionCertifications ModalSkills & ProjectsDark animated gradient hero with scroll revealCertificates open in-page modal (no new tab)Bento-style skills grid + project cards

✨ Features

Single-file architecture — Everything (HTML + CSS + JS + embedded assets) lives in one index.html file. No build process required.
Animated live gradient background — Canvas-based WebGL-style orbs that react and move in real time.
Scroll-reveal animations — Sections fade and slide in using IntersectionObserver as you scroll.
3D tilt effect — Project and certification cards tilt in 3D on mouse hover using CSS transform-style: preserve-3d.
In-page certificate modal — Clicking "View" on any certificate opens it in an overlay modal with a smooth animation. No new tab opened. Press Esc or click outside to close.
Certificates embedded as base64 — All certificate images are embedded directly in the HTML so they load instantly with no external dependency.
CV download — Resume PDF is embedded as a base64 data URI for direct one-click download.
Scroll progress bar — A thin gradient bar at the top of the viewport tracks reading progress.
Active nav highlighting — The nav link for the current section auto-highlights as you scroll.
Fully responsive — Adapts cleanly from desktop (1100px+) down to mobile (320px).
Custom scrollbar — Gradient-styled minimal scrollbar.
Animated noise/grain overlay — Subtle film-grain texture via inline SVG filter for depth.
Google Fonts — Bricolage Grotesque (headings), Lora (italic accents), DM Sans (body).


📁 Repository Structure
portfolio/
│
├── index.html          ← The entire portfolio (rename anshul_portfolio_v4.html → index.html)
├── README.md           ← This file
└── LICENSE             ← MIT License (optional)

⚠️ Important for deployment: Rename anshul_portfolio_v4.html to index.html before pushing. GitHub Pages and Netlify both look for index.html as the entry point.


🛠️ Tech Stack
LayerTechnologyStructureHTML5 (semantic tags)StylingCSS3 (custom properties, grid, flexbox, animations)InteractivityVanilla JavaScript (ES6+)BackgroundHTML5 Canvas APIFontsGoogle Fonts CDNAssetsBase64 embedded (images + PDF)
No npm. No webpack. No React. No dependencies. 🎉

🚀 Deployment Guide
Option 1 — GitHub Pages (Free & Recommended)

Fork or upload this repository to your GitHub account.
Rename anshul_portfolio_v4.html → index.html.
Go to your repo → Settings → Pages.
Under Source, select main branch and / (root) folder.
Click Save.
Your site will be live at:

   https://<your-username>.github.io/<repo-name>/
Example: https://janshul28.github.io/portfolio

⏱️ It may take 1–2 minutes for the site to go live after enabling Pages.


Option 2 — Netlify (Drag & Drop, No Account Needed)

Go to https://app.netlify.com/drop
Rename your file to index.html
Drag and drop the file (or folder) onto the page
Netlify will give you a live URL instantly — e.g., https://anshul-portfolio.netlify.app
Optional: connect your GitHub repo for auto-deploy on every push


Option 3 — Vercel

Install Vercel CLI: npm i -g vercel
In your project folder run: vercel
Follow the prompts — it will auto-detect static HTML and deploy instantly.


Option 4 — Run Locally
No server needed. Just open the file directly in your browser:
bash# Clone the repo
git clone https://github.com/janshul28/portfolio.git

# Navigate into it
cd portfolio

# Open in browser (macOS)
open index.html

# Open in browser (Windows)
start index.html

# Open in browser (Linux)
xdg-open index.html

🗂️ Sections
SectionDescriptionHeroName, role, animated gradient, Download CV buttonAboutBio, photo placeholder, chips, linksSkills4-column bento grid — Languages, Tools, Mobile Dev, Soft SkillsProjectsWeather App (Kotlin), EV Analysis (Tableau/SQL), Hotel BI DashboardTrainingAndroid Dev training at LPU with certificate viewerCertifications5 certificates — Infosys Springboard, Udemy, LPU — all viewable in modalParticipationTVS Credit EPIC, CTF, Cyber Security SymposiumEducationLPU B.Tech CSE, Class XII & X at Shri Maheswari SchoolContactEmail, Phone, LinkedIn, GitHub

🎨 Design Tokens
The entire color palette is defined as CSS custom properties at the top of the <style> block — easy to retheme:
css:root {
  --bg:      #080810;   /* Page background */
  --card:    #13131f;   /* Card background */
  --blue:    #6096f8;   /* Primary accent */
  --violet:  #a78bfa;   /* Secondary accent */
  --green:   #34d399;   /* Success / Training */
  --rose:    #fb7185;   /* Danger / Close button */
  --text:    #eeeef5;   /* Primary text */
  --text2:   #b0b0c8;   /* Secondary text */
}

📬 Contact
PlatformLink📧 Emailjanshul28082003@gmail.com💼 LinkedInlinkedin.com/in/anshuljain028🐱 GitHubgithub.com/janshul28📞 Mobile+91 9352439128

📄 License
This project is open source under the MIT License. Feel free to use it as a template for your own portfolio — just update the content with your own details!
