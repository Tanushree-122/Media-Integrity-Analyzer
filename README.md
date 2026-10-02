# Media Integrity Analyzer

A lightweight, browser-based learning tool designed to help users recognize manipulation in digital media. The app walks through short, fictional examples of misleading headlines and emotionally charged posts, then explains the red flags and teaches practical media-literacy habits.

## Overview

Media Integrity Analyzer is a static HTML/CSS/JavaScript project that presents:

- Challenge 1: Headline Detective
  - Compare a provocative headline to the article it references
  - Spot exaggeration, misleading scope, and weak sourcing
- Challenge 2: Emotion Detector
  - Identify emotional triggers such as fear, urgency, and social pressure
  - Learn how manipulative wording influences behavior and sharing
- Dashboard summary
  - Review what was learned
  - See the biggest red flag from the session
  - Get actionable habits to apply in everyday media consumption

The examples in the app are fictional and created for educational use, but the techniques mirror patterns commonly seen in real news, ads, and social posts.

## Features

- Interactive media-literacy lesson flow
- Randomized headline and emotional-trigger scenarios
- Click-to-flag phrase analysis
- Reveal-and-explain feedback after each challenge
- Score-based dashboard and learning summary
- Responsive single-page layout

## Project Structure

```text
Media-Integrity-Analyzer/
├── index.html
├── README.md
└── (No build tooling required)
```

## How to Run

Because this is a static web app, you can run it in any modern browser.

### Option 1: Open directly

Open `index.html` in your browser.

### Option 2: Serve locally

From the project directory, run:

```bash
python -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

## Tech Stack

- HTML
- CSS
- JavaScript

## Educational Goal

This project encourages critical thinking around:

- misleading headlines
- emotional manipulation in content
- source credibility
- evidence-based interpretation
- responsible sharing habits

## License

This project is provided for educational and demonstration purposes.

## Notes

The repository currently contains a single front-end page and is intentionally simple to make it easy to explore, modify, and extend. If you want, it can later be expanded with:

- more scenarios
- a real scoring backend
- user authentication
- downloadable lesson content
- multilingual support
