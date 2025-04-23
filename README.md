# Simple-Portfolio
A simple, modern, single-page portfolio template designed for easy editing and deployment. Showcase your skills, projects, and contact information with a clean and animated interface.

[![Netlify Deploy](https://img.shields.io/github/forks/cyberboyayush/Simple-Portfolio?style=for-the-badge)](https://github.com/CyberBoyAyush/Simple-Portfolio)
[![Netlify Deploy](https://img.shields.io/github/stars/cyberboyayush/simple-portfolio?style=for-the-badge)](https://github.com/CyberBoyAyush/Simple-Portfolio)

<!-- Add your screenshot here -->
![Portfolio Screenshot](/image.png) 
![Portfolio Screenshot](/image-2.png) 
![Portfolio Screenshot](/iamge-3.png) 
<!-- Make sure to add a screenshot.png file to the repository root, or update the path above -->

# Features
- **[X] Single Page Layout:** All content is accessible on a single, scrollable page for a seamless user experience.
- **[X] Modern & Animated Design:**
    - **Hero Section:** Features a gradient background, Particles.js animation, floating bubbles, and a typing effect for the title.
    - **Smooth Scrolling:** Navigating between sections is smooth.
    - **Hover Effects:** Interactive elements like buttons and project cards have subtle hover animations.
    - **Gradient Text:** Headings use eye-catching gradient effects.
- **[X] Key Sections Included:**
    - **Hero:** Introduction with profile picture, name, title, and call-to-action buttons.
    - **About Me:** A brief section to introduce yourself.
    - **Skills:** Display your skills with animated progress bars.
    - **Projects:** Showcase your featured projects with images/icons, descriptions, tech tags, and links.
    - **Tools I Use:** Highlight the technologies and tools you frequently work with.
    - **Contact Form:** Integrated Formspree contact form for easy communication.
    - **Contact Links:** Direct links to your social media profiles and email.
- **[X] Responsive Design:** Built with Tailwind CSS, ensuring the portfolio looks great on all devices (desktops, tablets, and mobiles).
- **[X] Easy To Edit:** Primarily requires editing the `index.html` file. No complex build steps needed.
- **[X] Easy to Deploy:** Simple deployment options available for free hosting platforms.
- **[X] 24x7 Uptime:** Deploy on services like GitHub Pages or Netlify for reliable availability.
- **[X] Support:** Reach out if you need help (contact details below).

## Dont Forget To [🌟Star](https://github.com/CyberBoyAyush/Simple-Portfolio/fork) and [🍴Fork](https://github.com/CyberBoyAyush/Simple-Portfolio/fork) This Repo 💙

# Need Help?
[![twitter badge](https://img.shields.io/badge/@CyberBoyAyush-30302f?style=for-the-badge&logo=twitter)](https://twitter.com/CyberBoyAyush)
[![telegram badge](https://img.shields.io/badge/@CyberBoyAyush-30302f?style=for-the-badge&logo=telegram)](https://t.me/CyberBoyAyush)
[![mailid badge](https://img.shields.io/badge/CyberBoyAyush-30302f?style=for-the-badge&logo=gmail)](mailto:contact@cyberboyayush.in)

# Clone This Repo
`git clone https://github.com/CyberBoyAyush/Simple-Portfolio.git`
Navigate into the cloned directory:
`cd Simple-Portfolio`

# Make Your Edits
All primary edits happen within the `index.html` file. Open it in your favorite code editor.

1.  **Profile Picture:** Replace `profile.png` in the root directory with your own image (keep the filename `profile.png` or update the `src` attribute in the `<img>` tag within the Hero section).
2.  **Hero Section:**
    *   Update the `<h1>` tag with your name or desired title.
    *   Modify the `<p>` tag with the typing effect to reflect your role or tagline.
    *   Adjust the `href` attributes in the call-to-action buttons if needed.
3.  **About Me Section:** Edit the text within the `<p>` tag to write your personal introduction.
4.  **Skills Section:**
    *   Modify the skill names (e.g., "Python", "PHP").
    *   Adjust the percentage text and the `style="width: ...%"` attribute for each `skill-progress-bar` div to match your proficiency.
5.  **Projects Section:**
    *   For each project `div`:
        *   Update the icon (`<i>` tag) or add an `<img>` tag for a project preview.
        *   Change the project title (`<h3>`).
        *   Write a brief project description (`<p>`).
        *   Update the technology tags (`<span>` elements).
        *   Set the correct URLs for the live demo/external link (`<a>` tag with `fa-external-link-alt`) and GitHub repository (`<a>` tag with `fa-github`). Add `#` if a link is not available.
    *   Update the "View More Projects" button link if necessary.
6.  **Tools Section:** Modify the icons (`<i>` tags) and names (`<p>` tags) to reflect the tools you use.
7.  **Contact Form Section:**
    *   **Crucially:** Replace `your-form-id` in the `<form>` tag's `action` attribute (`action="https://formspree.io/f/your-form-id"`) with your actual Formspree form endpoint ID. Sign up at [Formspree.io](https://formspree.io/) to get one.
8.  **Contact Links Section:** Update the `href` attribute for each social media/contact link (`<a>` tags) to point to your profiles.
9.  **Footer:** Update the name and link in the footer if desired.
10. **Title & Favicon:**
    *   Change the `<title>` tag in the `<head>` section.
    *   Replace `profile.png` in the `<link rel="icon">` tag if you want a different browser tab icon.

# Push Edited Code On Github
```
git add .
git commit -m "Type Your Message"
git remote remove origin
git remote add origin {your_repo}
git push origin [branch_name]
```
- Instead of your_repo add your repo link.
- Instead of branch_name add origin branch (default is master).

# Deploy Simple-Portfolio on Github Pages
GitHub Pages is a great free option for hosting static websites directly from your GitHub repository.
**Go to your repo >> settings >> pages >> source >> select master (or main) branch >> select / (root) folder >> now click on save**
Your site will be available at `https://<your-username>.github.io/<your-repo-name>/`.

# Deploy Simple-Portfolio on Netlify
Netlify offers robust free hosting for static sites with features like continuous deployment, forms, and more.

## Click on below button to deploy it on Netlify
[![Netlify Deploy](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/CyberBoyAyush/Simple-Portfolio)