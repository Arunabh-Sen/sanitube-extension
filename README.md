# Sanitube

Sanitube is a browser extension and companion website that helps users detoxify their YouTube feed by automatically recommending and surfacing high-quality videos on technical topics such as Rust, AI, DevOps, and more.

## Overview

The goal of Sanitube is to reduce distractions on YouTube by surfacing technical content curated by topic. The browser extension opens relevant videos in separate tabs to nudge the user toward learning-focused browsing. The landing page provides an overview of how the tool works and links to the extension.

## Leaky Code Design

The website features a unique background with floating code snippets that gently move around the screen. This "leaky code" effect visually represents how the extension filters out noise from YouTube, letting only useful tech content flow through.

## Features

- One-click video detox for selected topics
- Automatically opens top-rated YouTube videos
- Topics include Rust, AI, DevOps, Python, React, and more
- Lightweight and privacy-friendly (no data is stored)
- Responsive landing website built with modern UI libraries

## Extension

The extension allows users to:

- Choose a technical topic from a dropdown
- Instantly open several curated YouTube videos on that topic
- Skip distractions and refocus on learning

## Screenshots

![Screenshot 2025-06-14 184453](https://github.com/user-attachments/assets/5fa7f3d0-f752-4366-9362-281523428a04)
![Screenshot 2025-06-14 184508](https://github.com/user-attachments/assets/811cc4fc-d4ae-4022-a00f-cd473b8c49d1)
![Screenshot 2025-06-14 184520](https://github.com/user-attachments/assets/f2ceee61-4f12-484d-80da-b40e777fae29)
![Screenshot 2025-06-14 184538](https://github.com/user-attachments/assets/6a1541bd-7d34-4486-b0a7-05387f4f42d8)
![image](https://github.com/user-attachments/assets/b43248bf-0229-49bf-86ce-686b3d3f68b0)

### Usage

1. Install the extension manually or from the Chrome Web Store (once published).
2. Click the extension icon in your browser.
3. Select a topic and click "Start Detox".
4. Multiple YouTube tabs will open with relevant videos.

## Website

The website acts as a landing page and introduction to the Sanitube extension. It includes:

- A hero section with animated background code snippets
- Clear call-to-action buttons
- Instructions on how the extension works
- Link to download the extension

## Installation

To run locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/sanitube.git
cd sanitube
```

### 2. Run the website

```bash
cd website
npm install
npm run dev
```

### 3. Load the extension locally in chrome browser

1. Go to
```link
chrome://extensions/
```
2. Enable "Developer Mode"
3. Click "Load unpacked"
4. Select the extension/ folder from this repo

### 4. Folder structure

```pgsql
sanitube/
├── extension/          # Chrome extension files
│   ├── background.js
│   ├── content.js
│   ├── popup.js
│   ├── popup.html
│   ├── style.css
│   └── manifest.json
│
├── website/            # Landing website (Next.js app)
│   ├── components/
│   ├── pages/
│   ├── public/
│   └── package.json
```

### 5. Tech Stack

1. JavaScript
2. Chrome Extensions API
3. React
4. Tailwind CSS
5. Framer Motion

### 6. Contributions

Contributions, issues, and feature requests are welcome. Please fork the repository and open a pull request with your improvements.
