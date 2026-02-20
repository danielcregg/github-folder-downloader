# GitHub Folder Downloader

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

A sleek, modern web application that allows you to download any folder from a GitHub repository without cloning the entire repo.

## Overview

GitHub Folder Downloader is a lightweight, client-side web tool built with vanilla JavaScript and modern web technologies. It uses the GitHub API to fetch folder contents recursively, packages them into a ZIP file, and delivers the download directly in the browser. No server-side processing or authentication is required. The tool is hosted on GitHub Pages and can also be triggered via URL parameters for easy integration.

**Live Demo:** [https://danielcregg.github.io/github-folder-downloader](https://danielcregg.github.io/github-folder-downloader)

## Features

- **One-Click Downloads** - Paste a GitHub folder URL and click download
- **Smart ZIP Packaging** - Automatically maintains the original folder structure
- **Modern UI/UX** - Elegant glassmorphism design with smooth animations
- **Responsive Design** - Works on both desktop and mobile devices
- **Progress Tracking** - Real-time download progress indication
- **URL Parameter Support** - Trigger downloads via URL query parameters

## Prerequisites

- A modern web browser (Chrome, Firefox, Safari, or Edge)
- No installation required for the hosted version

## Getting Started

### Installation

**Option 1: Use the hosted version**

Visit [https://danielcregg.github.io/github-folder-downloader](https://danielcregg.github.io/github-folder-downloader)

**Option 2: Self-host**

1. Clone the repository:
   ```bash
   git clone https://github.com/danielcregg/github-folder-downloader.git
   cd github-folder-downloader
   ```

2. Open `index.html` in any modern web browser.

### Usage

**Basic Usage:**

Navigate to the app and paste a GitHub folder URL into the input field, then click **Download**.

**With URL Parameter:**
```
https://danielcregg.github.io/github-folder-downloader/?url=https://github.com/user/repo/tree/main/folder
```

## Tech Stack

- **HTML5** - Page structure
- **CSS3 / TailwindCSS** - Styling with glassmorphism and gradient effects
- **JavaScript (ES6)** - GitHub API interaction, ZIP generation, and download handling
- **JSZip** - Client-side ZIP file creation
- **FileSaver.js** - Browser-based file saving
- **Animate.css** - UI animations
- **GitHub Pages** - Static site hosting

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
