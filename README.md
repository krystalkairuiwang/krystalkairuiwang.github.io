# Jekyll Portfolio Template

A minimal, responsive, and customizable portfolio template for students and professionals. Built with Jekyll and designed for free hosting on GitHub Pages.

[](https://opensource.org/licenses/MIT)
[](https://www.google.com/search?q=https://web.duke.edu/)
[](https://jekyllrb.com)

This template was created to provide a simple, elegant way to showcase projects in more detail than a resume allows. It is designed to be easily configured and deployed by anyone, regardless of their technical background.

### Live Demo

  * **Original Site:** [michaelscutari.com](https://michaelscutari.com)
  * **Example Fork:** [isabeldudlyke.github.io](https://www.google.com/search?q=https://isabeldudlyke.github.io)

-----

### Features

  * **No-Cost Hosting:** Deploy for free using GitHub Pages.
  * **Easy Content Management:** All content is managed through simple Markdown files.
  * **Project Showcase:**
      * Dynamic filtering by 'Professional' and 'Personal' categories.
      * Priority system to feature your most important work.
      * Status badges for new or in-progress projects.
  * **Responsive Design:** A clean, modern aesthetic that looks great on any device.
  * **Technical Support:**
      * Built-in SEO optimization (`jekyll-seo-tag`).
      * MathJax support for rendering LaTeX equations.
      * Syntax highlighting via Rouge.
      * Dark mode ready and easily customizable.

### Quick Start

1.  **Fork the Repository**
    Click the "Fork" button on the top right of the repository page. This will create a copy of the template under your own GitHub account.

2.  **Rename the Repository**
    Navigate to your new repository's **Settings**. Rename the repository to `YOUR-USERNAME.github.io`.

3.  **Customize Your Information**
    Clone the repository to your local machine and edit `_config.yml` with your personal details:

    ```yaml
    title: "Your Name"
    description: "A brief tagline or description of yourself."
    url: "https://YOUR-USERNAME.github.io"
    ```

4.  **Deploy**
    Commit and push your changes. Your site will be live in a few minutes.

    ```bash
    git add .
    git commit -m "feat: Initial site customization"
    git push origin main
    ```

### Adding and Customizing Content

#### Projects

To add a new project, create a new Markdown file in the `_projects/` directory. Use the following frontmatter format:

```yaml
---
title: "Your Awesome Project"
date: 2025-07-14
category: "personal"  # or "professional"
priority: 1           # 1-10, lower is more prominent
header_image: "/assets/images/your-project-image.jpg"
description: "A short description that will appear on the project card."
technologies:
  - Python
  - Jekyll
  - Docker
---

The main content of your project goes here, written in Markdown. You can include images, code blocks, and more.
```

#### Pages

  * **About Page:** Edit `index.md`.
  * **Contact Page:** Edit `contact.md`.
  * **Resume:** Replace the existing PDF at `assets/scutari_resume.pdf` with your own.

#### Styling

Basic style variables like colors and fonts can be modified in `assets/css/style.scss`. The site navigation can be edited in `_layouts/default.html`.

### Local Development

To run and test the site on your local machine:

1.  **Install Dependencies:**
    ```bash
    bundle install
    ```
2.  **Run the Jekyll Server:**
    ```bash
    bundle exec jekyll serve
    ```
3.  **Preview:**
    Open your browser to `http://localhost:4000`.

### License

This project is licensed under the **MIT License**. See the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

### Acknowledgments

  * This project was inspired by the work of [Shaan Yadav](https://www.google.com/search?q=https://github.com/shaanyadav).
  * Built with [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).
