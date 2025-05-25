# 🐧💻 Learn Linux :) : An Educational HTML Website 🎓
_An HTML-based educational website dedicated to the Linux operating system, covering distributions, installation, commands, and Linus Torvalds, with custom styling and Google Fonts._

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![Google Fonts](https://img.shields.io/badge/Google%20Fonts-Lato-4285F4.svg?logo=googlefonts)](https://fonts.google.com/specimen/Lato)

## 📋 Table of Contents
1.  [Overview](#-overview)
2.  [Key Features](#-key-features)
3.  [Screenshots (Conceptual)](#-screenshots-conceptual)
4.  [Technical Stack & Requirements](#-technical-stack--requirements)
5.  [Local Setup & Viewing](#️-local-setup--viewing)
6.  [Website Usage & Navigation](#️-website-usage--navigation)
7.  [File Structure](#-file-structure)
8.  [Important Notes & Considerations](#-important-notes--considerations)
9.  [Contributing](#-contributing)
10. [License](#-license)
11. [Contact](#-contact)

## 📄 Overview

**Learn Linux :)** is a static educational website built with HTML and CSS, designed to provide information about the Linux operating system. The site structure includes a top navigation menu and a corresponding left sidebar, offering access to sections on Linux Distributions, Installation, common Commands, and information about Linus Torvalds. It features a "top bar" area with a Linux logo and an introductory quote from Linus Torvalds. The main content area currently holds placeholder text. Styling is managed by a custom `style.css` and typography is enhanced with the Google Font "Lato". The project aims to be a beginner-friendly resource for those looking to learn about Linux.

## ✨ Key Features

*   🧭 **Dual Navigation System**:
    *   **Top Navigation Menu**: Provides primary links to different sections: Home, Distributions, Installation, Commands, and Linus Torvalds.
    *   **Left Sidebar**: Mirrors the top menu links for alternative and easy access to content sections.
*   🐧 **Informative Top Bar**:
    *   Displays a Linux logo (`linux.png`).
    *   Includes a project description or introductory text alongside a quote from Linus Torvalds.
*   📝 **Content Section**:
    *   A dedicated area for detailed content. Currently features a "Why Linux?" heading with "Lorem ipsum" placeholder text, intended to be replaced with actual educational material.
*   🦶 **Footer**:
    *   Contains notes about the site's purpose and copyright information (dating back to 2014).
*   🔍 **SEO Meta Tags**:
    *   Includes `<meta name="description">` and `<meta name="keywords">` tags with relevant terms (e.g., Linux, Ubuntu, Bash, Open Source, Command Line) to aid search engine discovery.
*   🎨 **Custom Styling & Typography**:
    *   Styled with a custom stylesheet (`style.css`) to define the layout, colors, and overall appearance.
    *   Utilizes the "Lato" Google Font, linked via `https://fonts.googleapis.com`, for clean and readable typography.
*   🇬🇧 **English Language Content**: The website structure and placeholder text are in English (`lang="en"`), aiming for broad accessibility.

## 🖼️ Screenshots (Conceptual)

**Coming soon!**

_This section would ideally show screenshots of: the website's homepage featuring the top bar with logo and quote, the navigation menu, the sidebar, the main content area (even with placeholder text), and the footer._

## 🛠️ Technical Stack & Requirements

### Core Technologies:
*   **Structure**: HTML5
*   **Styling**: CSS3 (`style.css`)
*   **Fonts**: Google Fonts (Lato)

### Requirements:
*   **Web Browser**: Any modern web browser (e.g., Google Chrome, Mozilla Firefox, Safari, Microsoft Edge).
*   **Internet Connection**: Required to load the "Lato" Google Font from `https://fonts.googleapis.com`.
*   **Local Assets**: All specified CSS and image files must be present in the correct locations relative to `index.html`.
    *   `style.css` (root directory or linked path)
    *   `linux.png` (Linux logo image, path as specified in HTML/CSS, likely root or an `images/` folder)

## ⚙️ Local Setup & Viewing

1.  **Clone or Download the Repository**:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```
    *(Replace `<repository-url>` and `<repository-directory>` with your specific details, or simply download the files into a local folder).*

2.  **Ensure Asset Placement**:
    *   Verify that `style.css` is in the same directory as `index.html` (or update the link in `index.html` if it's in a subfolder like `css/`).
    *   Confirm that `linux.png` is present and its path in the HTML/CSS is correct (e.g., if it's in an `images/` subfolder, the path should be `images/linux.png`).

3.  **Open in Browser or Host Locally**:
    *   **Directly in Browser**: You can usually open `index.html` directly in your web browser (File > Open File).
    *   **Using a Simple HTTP Server (Recommended for consistent behavior)**:
        If you have Python installed, navigate to the project's root directory in your terminal and run:
        ```bash
        python -m http.server 8000
        ```
        Then, open your web browser and go to `http://localhost:8000`.
    *   Alternatively, use any other local web server solution (e.g., Live Server extension in VS Code, XAMPP/MAMP htdocs).

## 💡 Website Usage & Navigation

1.  Open `index.html` in your web browser using one of the methods described above.
2.  **Interface**:
    *   **Navigation Menu (Top)**: Click on links like "Home," "Distributions," "Installation," "Commands," or "Linus Torvalds" to navigate to (currently placeholder) respective pages or sections.
    *   **Sidebar (Left)**: Offers the same set of navigation links as the top menu for alternative access.
    *   **Top Bar**: View the Linux logo (`linux.png`) and an introductory message about the project, including a quote from Linus Torvalds.
    *   **Main Content Area**: Read the content displayed under headings like "Why Linux?". Currently, this section contains "Lorem ipsum" placeholder text.
    *   **Footer**: Contains information about the site's purpose and copyright details.
3.  **Actions**:
    *   Use either the top navigation menu or the left sidebar to attempt navigation. Note that these links (`distribution.html`, `commands.html`, etc.) are **placeholders** and will likely result in "File not found" errors unless the corresponding HTML pages are created.
    *   The primary content in the "Why Linux?" section is placeholder text and needs to be replaced with actual educational material about Linux.

## 🗂️ File Structure

The project is expected to have the following basic file structure:

*   `index.html`: The main HTML file for the homepage, containing the structure for the top bar, navigation menu, sidebar, main content area, and footer.
*   `style.css`: The CSS file for styling all visual elements of the website.
*   `linux.png`: The image file for the Linux logo.
*   (Potentially) Placeholder HTML files for other sections like `distribution.html`, `installation.html`, `commands.html`, `linus_torvalds.html`.
*   `README.md`: This documentation file.

*(It's common practice to organize CSS and images into subfolders like `css/` and `img/` or `assets/`. If so, paths in `index.html` and `style.css` must reflect this organization.)*

## 📝 Important Notes & Considerations

*   **English Language**: The website is presented in English (`lang="en"`), aiming for broad accessibility to learners worldwide.
*   **Placeholder Links & Content**:
    *   Navigation links in both the top menu and sidebar (e.g., to `distribution.html`, `commands.html`) are currently placeholders. The corresponding HTML pages need to be created and populated with content.
    *   The main content section under "Why Linux?" uses "Lorem ipsum" placeholder text and requires replacement with actual Linux-related information.
*   **Image Paths**: The correct path to `linux.png` is crucial for it to display in the top bar.
*   **Static Nature**: This is a static HTML/CSS website. Any dynamic features (like interactive command tutorials or user accounts) would require JavaScript and/or a backend system.
*   **Google Fonts Dependency**: The site relies on an internet connection to fetch the "Lato" font from Google Fonts. Consider adding local font fallbacks in `style.css` for offline viewing or to ensure consistent appearance if Google Fonts are unavailable.
*   **`style.css` Implementation**: The overall visual design, layout (including the top bar, sidebar, and content area), and responsiveness depend heavily on the CSS rules defined in `style.css` (which is assumed to be provided but not detailed in the overview).

## 🤝 Contributing

Contributions to **Learn Linux :)** are highly encouraged, especially in areas like:

*   Populating the placeholder sections (Distributions, Installation, Commands, Linus Torvalds) with accurate and helpful content.
*   Creating the corresponding HTML pages for the navigation links.
*   Improving the CSS styling, layout, and responsiveness.
*   Adding interactive elements using JavaScript (e.g., a simple command lookup tool).
*   Correcting or updating information.

1.  Fork the repository.
2.  Create a new branch for your feature or content addition (`git checkout -b feature/AddUbuntuPage` or `content/UpdateCommandsSection`).
3.  Make your changes (HTML, CSS, textual content).
4.  Commit your changes (`git commit -m 'Content: Add initial content for Ubuntu page'`).
5.  Push to the branch (`git push origin content/UpdateCommandsSection`).
6.  Open a Pull Request.

## 📃 License

This project is licensed under the **MIT License**.
(If you have a `LICENSE` file in your repository, refer to it: `See the LICENSE file for details.`)

## 📧 Contact

Project developed by **Adrian Lesniak**.
For questions, feedback, or to discuss contributions, please open an issue on the GitHub repository or contact the repository owner.

---
💡 _Your friendly starting point for exploring the world of Linux!_
