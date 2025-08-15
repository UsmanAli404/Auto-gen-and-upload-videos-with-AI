# 🎥 AI-Powered Short-Form Video Automation

Generate AI videos with **Seedance** & **Blotato**, then publish directly to TikTok, YouTube Shorts, and Instagram Reels — without manual editing or uploading.

---

## 👥 Who Is This For?
This template is built for:
- Content creators
- Social media managers
- Marketing teams
- AI enthusiasts

Perfect for automating the creation of short, visually engaging videos across popular platforms.

---

## ❓ Problem It Solves
Creating high-quality, engaging short-form videos typically involves:
- Coming up with fresh ideas
- Writing detailed scene prompts
- Producing realistic visuals and audio
- Editing and stitching clips
- Publishing to multiple platforms

This workflow **automates the entire process**, saving hours of effort while maintaining consistent, AI-generated content ready for distribution.

---

## ⚙️ What the Workflow Does
An **end-to-end video production pipeline**:
1. **Idea Generation** – Uses OpenAI + LangChain to generate creative concepts.
2. **Prompt Creation** – Builds detailed video scene prompts with **Seedance AI**.
3. **Video Clip Generation** – Creates clips via **Wavespeed AI**.
4. **Sound Effects** – Adds audio with **Fal AI**.
5. **Video Stitching** – Combines clips and sound using **Fal AI’s ffmpeg API**.
6. **Metadata Logging** – Saves video info & links to **Google Sheets**.
7. **Publishing** – Uploads to **Blotato** and auto-posts to TikTok, YouTube, Instagram, and more.

---

## 🛠 Setup
1. Add your **OpenAI API key** in the LLM nodes.
2. Configure **Seedance** and **Wavespeed AI** credentials for video prompt & clip generation.
3. Add your **Fal AI API key** for sound effects and video stitching.
4. Connect your **Google Sheets** account for logging.
5. Set your **Blotato API key** and platform account IDs in the “Assign Social Media IDs” node.
6. Adjust the **Schedule Trigger** to control automation frequency.

---

## 🎯 Customization Tips
- Modify AI prompts to fit your niche (e.g., ASMR, product showcases, comedy).
- Add a Telegram or Slack preview step before publishing.
- Adjust scene count or video duration for your style.
- Disable unwanted platforms by turning off specific **HTTP Request** nodes.
- Tweak sound prompts to achieve different moods or effects.

---

## 🚀 Benefits
- Fully automated video production from idea to posting
- Consistent output for social media growth
- Saves hours of manual editing & uploading
- Scalable AI-driven creative workflow
