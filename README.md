
<div align="center"><p align="center">
  <img
    src="https://capsule-render.vercel.app/api?type=waving&color=1C1917&height=220&section=header&text=ARCHIVUM&fontSize=65&fontAlignY=40&desc=Autonomous%20Portfolio%20Catalogue%20%26%20Directory&descFontSize=16&descAlignY=62&fontColor=C5A880&stroke=8C704B&strokeWidth=1"
    width="100%"
    alt="ARCHIVUM Header"
  />
</p><a href="https://github.com/harshthakur750556/xeno-portfolio">
  <img
    src="https://readme-typing-svg.demolab.com?font=Cinzel&weight=600&size=18&duration=3000&pause=1000&color=8C704B&center=true&vCenter=true&width=650&height=45&lines=COLLECTION+MMXXVI+%E2%80%A2+OPUS+CURATUM;AUTONOMOUS+RECURSIVE+TREE+CATALOGUE;DYNAMIC+THREE.JS+3D+KINETIC+MONUMENT;DEPLOYED+SEAMLESSLY+ON+VERCEL+%26+GITHUB"
    alt="ARCHIVUM Animated Subtitle"
  />
</a><br /><p align="center">  <a href="https://github.com/harshthakur750556/xeno-portfolio/stargazers">
    <img
      src="https://img.shields.io/github/stars/harshthakur750556/xeno-portfolio?style=for-the-badge&logo=github&logoColor=C5A880&label=STARS&color=1C1917&labelColor=292524"
      alt="GitHub Stars"
    />
  </a>  <a href="https://github.com/harshthakur750556/xeno-portfolio/network/members">
    <img
      src="https://img.shields.io/github/forks/harshthakur750556/xeno-portfolio?style=for-the-badge&logo=git&logoColor=C5A880&label=FORKS&color=1C1917&labelColor=292524"
      alt="GitHub Forks"
    />
  </a>  <a href="https://github.com/harshthakur750556/xeno-portfolio/blob/main/LICENSE">
    <img
      src="https://img.shields.io/badge/EDITION-MMXXVI-8C704B?style=for-the-badge&label=CURATED&labelColor=1C1917"
      alt="Edition MMXXVI"
    />
  </a>  <a href="https://discord.com/users/1508113317451923536">
    <img
      src="https://img.shields.io/badge/DISCORD-1508113317451923536-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=1C1917"
      alt="Discord"
    />
  </a></p><p align="center">
  <a href="https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fharshthakur750556%2Fxeno-portfolio">
    <img
      src="https://vercel.com/button"
      alt="Deploy with Vercel"
    />
  </a>
</p></div>---

🏛️ Exemplaris Overview

«ARCHIVUM is a standalone, museum-inspired portfolio repository catalogue engineered for automatic deployment on GitHub and Vercel.

It transforms the repository into a living digital archive by discovering portfolio HTML documents stored inside the "Portfolios/" directory, extracting their metadata, rendering live previews, and exposing each work through a unified catalogue interface.»

ARCHIVUM eliminates the need for a manually maintained portfolio registry.

Add a new HTML portfolio to "Portfolios/", commit it to GitHub, and the catalogue can discover it automatically.

---

✦ Core Capabilities

Capability| Description
⚡ Autonomous Sync| Automatically discovers portfolio ".html" documents inside "Portfolios/".
🌳 Recursive Indexing| Supports nested portfolio directories at arbitrary depth.
🖼️ Live Thumbnails| Renders actual portfolio pages through live iframe previews.
🧭 Metadata Extraction| Reads "<title>" and "<meta name="description">" from each document.
🏛️ Three.js Monument| Interactive procedural celestial sculpture forms the visual centrepiece.
📱 Responsive Preview| Inspect portfolios using desktop, tablet, and mobile viewport modes.
↗️ Direct Launch| Open any portfolio directly in a full browser tab.
⬇️ Direct Export| Download standalone portfolio HTML documents.
🚀 Vercel Ready| Designed for seamless static deployment.

---

🔭 Architectural Capabilities

<details open>
<summary><b>1. Recursive Portfolio Discovery</b></summary><br />ARCHIVUM treats "Portfolios/" as the canonical portfolio repository.

It recursively discovers HTML documents such as:

Portfolios/
├── portfolio-one/
│   └── index.html
│
├── portfolio-two/
│   └── showcase.html
│
└── portfolio-three/
    └── visual/
        └── index.html

The discovery system can identify:

- Root HTML documents within "Portfolios/"
- Nested HTML documents
- Nested "index.html" files
- Portfolio documents located multiple directory levels deep

The main root catalogue, "index.html", remains outside the portfolio collection and is not treated as a portfolio entry.

</details><details open>
<summary><b>2. Live Scaled Viewport Rendering</b></summary><br />Each catalogue card can render the actual portfolio document through a live iframe.

This avoids the need for manually generated screenshots.

Instead of:

HTML → Screenshot → Static Image

ARCHIVUM uses:

HTML → Live Document → Scaled iframe Preview

This means the preview can reflect the actual portfolio layout, typography, animation, images, and styling.

</details><details open>
<summary><b>3. Relative Asset Resolution</b></summary><br />Nested portfolios frequently reference resources using relative paths:

style.css
script.js
assets/logo.svg
images/hero.webp
fonts/custom.woff2

For example:

<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<img src="assets/logo.svg" alt="Logo">

When required, ARCHIVUM can establish the correct document base using:

<base href="./portfolio-directory/">

This allows relative CSS, JavaScript, image, font, and other asset references to resolve against the correct portfolio location.

</details><details open>
<summary><b>4. Metadata Intelligence</b></summary><br />Each portfolio can provide catalogue information directly through standard HTML metadata.

Document title

<title>Example Portfolio</title>

Document description

<meta
  name="description"
  content="A visual portfolio exploring computational architecture."
>

ARCHIVUM can then transform the document into a catalogue entry such as:

Example Portfolio
A visual portfolio exploring computational architecture.

No separate portfolio database is required.

</details><details open>
<summary><b>5. Three.js Celestial Monument</b></summary><br />The ARCHIVUM interface incorporates a procedural 3D sculpture inspired by classical astronomical instruments.

Alabaster Core

A dense geometric structure with procedural surface deformation based on mathematical wave functions.

Imperial Gold Nucleus

A luminous central structure representing a stellar or planetary core.

Kinetic Astrolabe

Multiple concentric orbital rings rotate around independent astronomical axes.

Interactive Mechanics

Mouse and touch interaction provide:

- Orbit control
- Drag interaction
- Inertial movement
- Momentum decay
- Cursor-responsive motion

The result is a digital monument rather than a conventional dashboard background.

</details><details open>
<summary><b>6. Multi-Device Portfolio Inspection</b></summary><br />Each portfolio can be inspected using multiple responsive viewport presets.

DESKTOP
TABLET   → 768px
MOBILE   → 380px

The purpose is to inspect the same portfolio from different display contexts without leaving ARCHIVUM.

</details><details open>
<summary><b>7. Launch & Export</b></summary><br />Each indexed portfolio can expose:

- Live preview
- Full-screen inspection
- Direct browser launch
- Responsive viewport switching
- Direct HTML download
- Portfolio metadata
- File information

This allows ARCHIVUM to function simultaneously as:

Portfolio Catalogue
        +
Digital Archive
        +
Preview System
        +
Distribution Layer

</details>---

🗂️ Repository Architecture

The repository intentionally contains one portfolio directory: "Portfolios/".

harshthakur750556/xeno-portfolio/
│
├── index.html
│   └── ARCHIVUM Catalogue Portal
│
├── Portfolios/
│   │
│   ├── portfolio-one/
│   │   ├── index.html
│   │   ├── style.css
│   │   ├── script.js
│   │   └── assets/
│   │
│   ├── portfolio-two/
│   │   └── index.html
│   │
│   └── portfolio-three/
│       ├── showcase.html
│       ├── style.css
│       └── assets/
│
├── LICENSE
└── README.md

Structural Principle

Repository Root
      │
      ├── index.html
      │      │
      │      └── ARCHIVUM
      │
      └── Portfolios/
             │
             ├── Portfolio A
             ├── Portfolio B
             ├── Portfolio C
             └── ...

"Portfolios/" is therefore the single source of portfolio content.

---

🧬 Discovery Pipeline

A typical discovery sequence looks like this:

Portfolios/
      │
      ▼
Recursive File Traversal
      │
      ▼
Find *.html
      │
      ▼
Read Document Metadata
      │
      ├── <title>
      ├── <meta name="description">
      └── File Information
      │
      ▼
Generate Catalogue Entry
      │
      ▼
Create Live Preview
      │
      ▼
Expose Controls
      │
      ├── Preview
      ├── Open
      └── Download

This architecture allows the repository to grow without requiring changes to a hard-coded portfolio list.

---

🖼️ Live Preview Architecture

Consider the following portfolio:

Portfolios/
└── museum/
    ├── index.html
    ├── style.css
    ├── script.js
    └── assets/
        ├── hero.jpg
        └── logo.svg

Its document may reference:

<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
<img src="assets/hero.jpg" alt="Hero">

ARCHIVUM preserves the portfolio's directory context so that these relative resources continue to resolve correctly when displayed inside the catalogue.

The important architectural requirement is:

Portfolio URL
      ↓
Correct document directory
      ↓
Correct relative resource resolution
      ↓
Correct iframe rendering

---

🔍 HTML Metadata Convention

For optimal ARCHIVUM integration, portfolios should expose a title and description.

Recommended structure

<!DOCTYPE html>
<html lang="en">
<head>

  <meta charset="UTF-8">

  <title>My Portfolio</title>

  <meta
    name="description"
    content="My portfolio exploring computational design and interactive systems."
  >

</head>

<body>

  <!-- Portfolio content -->

</body>
</html>

The metadata can then be consumed by the catalogue automatically.

---

🧪 Example Portfolio

A minimal compatible portfolio could look like:

<!DOCTYPE html>
<html lang="en">

<head>

  <meta charset="UTF-8">

  <title>Example Portfolio</title>

  <meta
    name="description"
    content="Example portfolio document for ARCHIVUM."
  >

  <link rel="stylesheet" href="style.css">

</head>

<body>

  <main>

    <h1>Example Portfolio</h1>

    <p>
      This document can be discovered and catalogued by ARCHIVUM.
    </p>

  </main>

  <script src="script.js"></script>

</body>

</html>

Place the project anywhere below:

Portfolios/

For example:

Portfolios/
└── example/
    ├── index.html
    ├── style.css
    └── script.js

---

🚀 Quick Start

1. Add a Portfolio

Create a directory inside "Portfolios/".

Example:

Portfolios/
└── my-new-project/
    ├── index.html
    ├── style.css
    ├── script.js
    └── assets/

Your portfolio can contain its own files and internal directory structure.

---

2. Commit the Portfolio

git add .
git commit -m "Add new portfolio opus"
git push origin main

---

3. Deploy

Vercel can deploy the repository directly.

Once the deployment reflects the latest commit, ARCHIVUM can discover the new portfolio from "Portfolios/".

---

🛠️ Technology Stack

<p align="left"><img
src="https://img.shields.io/badge/Three.js-r128-1C1917?style=flat-square&logo=threedotjs&logoColor=C5A880"
alt="Three.js"
/>

<img
src="https://img.shields.io/badge/Tailwind_CSS-CDN-1C1917?style=flat-square&logo=tailwindcss&logoColor=C5A880"
alt="Tailwind CSS"
/>

<img
src="https://img.shields.io/badge/Lucide-Icons-1C1917?style=flat-square&logo=lucide&logoColor=C5A880"
alt="Lucide Icons"
/>

<img
src="https://img.shields.io/badge/GitHub-REST_API-1C1917?style=flat-square&logo=github&logoColor=C5A880"
alt="GitHub REST API"
/>

<img
src="https://img.shields.io/badge/Vercel-Deployment-1C1917?style=flat-square&logo=vercel&logoColor=C5A880"
alt="Vercel"
/>

</p>Stack Overview

Presentation
├── HTML
├── CSS
└── JavaScript

Visual Engine
├── Three.js
└── WebGL

UI
├── Tailwind CSS
└── Lucide Icons

Repository Intelligence
└── GitHub API

Deployment
└── Vercel

---

🧭 System Architecture

                         GITHUB
                           │
                           ▼
                  ┌─────────────────┐
                  │   Repository    │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │   Portfolios/   │
                  └────────┬────────┘
                           │
                           ▼
                Recursive HTML Discovery
                           │
                           ▼
                  ┌─────────────────┐
                  │ Metadata Parser │
                  └────────┬────────┘
                           │
             ┌─────────────┼─────────────┐
             │             │             │
             ▼             ▼             ▼
          Title       Description    File Info
             │             │             │
             └─────────────┼─────────────┘
                           ▼
                  ┌─────────────────┐
                  │    ARCHIVUM     │
                  │    Catalogue    │
                  └────────┬────────┘
                           │
          ┌────────────────┼────────────────┐
          │                │                │
          ▼                ▼                ▼
     Live Preview     Three.js Art      Controls
          │                │                │
          └────────────────┼────────────────┘
                           ▼
                  ┌─────────────────┐
                  │     VERCEL      │
                  │   Production    │
                  └─────────────────┘

---

🏛️ Design Philosophy

ARCHIVUM is deliberately designed around the visual language of a classical archive.

Dark Stone
     +
Carrara Alabaster
     +
Imperial Gold
     +
Classical Typography
     +
Astronomical Geometry
     +
Modern WebGL
     =
ARCHIVUM

The objective is to make the interface feel less like a generic developer dashboard and more like a digital museum catalogue.

---

🎨 Design System

Element| Value
Primary Background| "#1C1917"
Secondary Background| "#292524"
Alabaster| "#FAF8F5"
Imperial Gold| "#C5A880"
Bronze| "#8C704B"
Stone Text| "#57534E"
Display Typeface| Cinzel
Body Typeface| System / Sans
Renderer| Three.js

---

📐 Portfolio Contract

ARCHIVUM is designed to work best when every portfolio follows a simple contract:

Portfolios/
└── <portfolio-name>/
    ├── index.html
    ├── CSS / JavaScript
    ├── images / fonts / assets
    └── optional nested resources

The portfolio itself remains independent.

ARCHIVUM does not need to rewrite the portfolio's application architecture.

It simply discovers, reads, previews, and launches it.

---

🛡️ HTML Rendering Rule

When HTML syntax needs to be displayed literally inside this README, it should always be placed inside a fenced code block.

Correct:

<base href="./portfolio/">
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>

Correct:

<title>
<meta>
<link>
<base>
<script>

Avoid placing raw HTML syntax directly inside ordinary Markdown paragraphs unless the HTML is intentionally meant to be rendered.

This prevents GitHub's Markdown renderer from interpreting the examples as actual page elements.

---

📦 Deployment Model

Local Development
       │
       ▼
Portfolios/
       │
       ▼
Git Commit
       │
       ▼
GitHub
       │
       ▼
Vercel Deployment
       │
       ▼
ARCHIVUM Runtime
       │
       ▼
Recursive Portfolio Discovery
       │
       ▼
Live Catalogue

---

✅ Adding a New Portfolio

1. Create directory
   ↓
2. Place portfolio inside Portfolios/
   ↓
3. Add index.html or another HTML entry point
   ↓
4. Include normal relative assets
   ↓
5. Commit to Git
   ↓
6. Push to GitHub
   ↓
7. Deploy through Vercel
   ↓
8. ARCHIVUM discovers the portfolio

No manual catalogue entry should be necessary.

---

👤 Architect & Curator

<div align="center"><br />Harsh Thakur

Lead Architect & Repository Curator

<br /><a href="https://github.com/harshthakur750556">
  <img
    src="https://img.shields.io/badge/GitHub-harshthakur750556-1C1917?style=for-the-badge&logo=github&logoColor=C5A880&labelColor=292524"
    alt="GitHub Profile"
  />
</a> 

<a href="https://discord.com/users/1508113317451923536">
  <img
    src="https://img.shields.io/badge/Discord-harsh750556-5865F2?style=for-the-badge&logo=discord&logoColor=white&labelColor=1C1917"
    alt="Discord"
  />
</a><br />
<br />꧁༒⟁Ⱨ₳Ɽ₴Ⱨ ₮Ⱨ₳₭ɄⱤ⟁༒꧂

<br /><sub>ANNO MMXXVI • OPUS CURATUM • ALL RIGHTS RESERVED</sub>

</div>---

<div align="center">ARCHIVUM

COLLECTION MMXXVI • OPUS CURATUM

A living catalogue of digital works.

</div>
