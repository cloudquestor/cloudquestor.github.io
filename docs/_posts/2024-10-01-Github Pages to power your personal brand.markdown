---
layout: post
title:  "How I built my website under 30 mintues!"
date:   2024-10-01 03:32:52 -0400
categories: Website development
---

A personal website serves as a powerful branding tool for developers by showcasing their skills, projects, and professional journey in a polished and accessible manner. It creates a unique online presence that sets them apart in a competitive job market, allowing potential employers and collaborators to see their expertise and creativity firsthand. 

GitHub Pages is a free and user-friendly hosting service that allows you to create and publish static websites directly from a GitHub repository.

Ideal for personal projects, portfolios, documentation, or blogs, GitHub Pages seamlessly integrates with Git version control, making it easy to manage and update your site. With support for custom domains, Jekyll integration for dynamic content, and a variety of templates, GitHub Pages empowers developers and non-developers alike to share their work on the web effortlessly.

Here are the steps to build a website using GitHub Pages:

### 1. **Create a GitHub Account**
   - If you don’t already have one, sign up for a free GitHub account at [github.com](https://github.com).

### 2. **Create a New Repository**
   - Go to your GitHub profile and click on the "+" icon in the top right corner.
   - Select "New repository."
   - Name your repository as `username.github.io`, replacing `username` with your GitHub username.
   - Choose "Public" and check "Initialize this repository with a README" if desired.

### 3. **Clone the Repository Locally**
   - Open your terminal (or Git Bash on Windows).
   - Clone your new repository using the following command:
     ```bash
     git clone https://github.com/username/username.github.io.git
     ```

### 4. **Create Your Website Files**
   - Navigate to the cloned repository folder:
     ```bash
     cd username.github.io
     ```
   - Create an `index.html` file, which will serve as the homepage of your website.
   - Add your HTML content to `index.html`. You can also add CSS and JavaScript files as needed.

### 5. **Commit Your Changes**
   - After creating your website files, stage and commit them:
     ```bash
     git add .
     git commit -m "Initial commit"
     ```

### 6. **Push Changes to GitHub**
   - Push your local changes to GitHub:
     ```bash
     git push origin main
     ```

### 7. **Enable GitHub Pages**
   - Go to your repository on GitHub.
   - Click on "Settings."
   - Scroll down to the "Pages" section.
   - Under "Source," select the branch (typically `main`) and folder (usually `/ (root)`).
   - Click "Save."

### 8. **Access Your Website**
   - After a few moments, your site will be live at `https://username.github.io`.
   - You may need to refresh the page to see your changes.

### 9. **Update Your Website**
   - To make changes, modify your files locally, then commit and push your updates as before:
     ```bash
     git add .
     git commit -m "Update website"
     git push origin main
     ```

### 10. **Optional: Use a Static Site Generator**
   - For more complex sites, consider using a static site generator like Jekyll, Hugo, or Gatsby. These tools can simplify content management and provide templates.

### Additional Tips:
- **Custom Domain:** If you have a custom domain, you can configure it in the GitHub Pages settings.
- **Themes:** Explore GitHub Pages themes for a quick and professional look.
- **Markdown Support:** GitHub Pages supports Markdown files, allowing for easy content creation.

By following these steps, you can successfully create and publish a website using GitHub Pages!