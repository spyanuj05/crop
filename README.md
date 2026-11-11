<div align="center">
  <img src="anime-boy-full.png" alt="Contentora Mascot" width="120" />
  <h1>👑 Contentora</h1>
  <p><strong>The Ultimate AI Creative Studio for Video Creators</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5" />
    <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3" />
    <img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E" alt="JavaScript" />
    <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white" alt="Node.js" />
    <img src="https://img.shields.io/badge/Express.js-404D59?style=for-the-badge" alt="Express.js" />
  </p>
</div>

---

## 📖 The Problem
Creating a single YouTube video or short film is a fragmented process. Creators waste hours jumping between **ChatGPT** (for scripts), **Midjourney** (for images), **Runway** (for video prompts), and **CapCut** (for editing). They lose their creative flow just trying to calculate scene timings and format SEO tags.

## 💡 The Solution
**Contentora** is an all-in-one AI production pipeline. You enter a single prompt, and our AI Director generates a complete, shootable video package in seconds.

### ✨ Key Features
- **🧠 Multi-Model AI Router:** Automatically routes requests to Groq (for lightning-fast generation), Google Gemini, or OpenRouter. If all fail, it falls back to a free Pollinations endpoint. **It never crashes.**
- **📦 1-Click Production Package:** Download a `.zip` file containing `script.md`, `prompts.txt`, `captions.srt`, and the generated `thumbnail.jpg`. Ready to drop into Premiere or CapCut.
- **🖼️ AI Thumbnail Generation:** Generates a clickable YouTube thumbnail based on the script context.
- **🎬 Interactive Storyboard:** Toggle between a slideshow view or a grid view of all scenes.
- **🌐 Community Remixing:** Publish your generated blueprints to the Community tab so other creators can load and remix them.
- **💾 Persistent History:** Uses `localStorage` to auto-save your last generation and history. Refresh the page without losing your work.
- **🔊 Built-in TTS:** Click the speaker icon on any scene to hear the voiceover using the browser's Web Speech API.

---

## 🛠️ Tech Stack
- **Frontend:** Vanilla HTML, CSS, JavaScript (Zero frameworks, incredibly fast, custom glassmorphism design).
- **Backend:** Node.js & Express.
- **AI Integrations:** 
  - Text Generation: Groq (Llama 3), Google Gemini 1.5 Flash, OpenRouter.
  - Image Generation: Pollinations.ai (Flux model).
- **Utilities:** JSZip (for the production package export), FontAwesome, Google Fonts (Orbitron & Poppins).

---

## 🚀 Getting Started (Local Setup)

### Prerequisites
You will need [Node.js](https://nodejs.org/) installed on your machine.

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/contentora.git
cd contentora
