# Meme Shorts Generator 🎥😂

This is a fully automated web app that generates funny meme videos using trending memes, a background video, and music. You can generate and download a ready-to-upload meme short (MP4) in a single click!

## 🚀 Features

- Auto-fetches trending memes via API
- Overlays memes on a background video with music
- Responsive web interface
- Download button appears after generation
- Replaces old video automatically
- Mobile-friendly UI
- Ready for deployment on Render

## 🛠 Tech Stack

- Python 🐍 (Flask, MoviePy)
- HTML5 + CSS3 + JavaScript
- Meme API (`https://meme-api.com/gimme`)
- Responsive Design

## 📁 Folder Structure

project/
│
├── assets/
│ ├── background_video.mp4
│ └── background_music.mp3
│
├── web/
│ ├── index.html
│ └── script.js
│
├── app.py
├── generate_video.py
├── requirements.txt
├── README.md
└── web/final_video.mp4 # Generated output

bash
Copy
Edit

## 🖥️ Local Setup

1. **Clone the Repo**
   ```bash
   git clone https://github.com/your-username/meme-shorts-generator.git
   cd meme-shorts-generator
Install Dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run the App

bash
Copy
Edit
python app.py
Access in Browser
Open http://127.0.0.1:5000 in your browser.

🌐 Deploy on Render
Create a new Web Service on Render

Connect your GitHub repo

Set the start command: gunicorn app:app

Use Python 3.10+ environment

Add requirements.txt and render.yaml if needed

📦 Requirements
Python 3.8+

moviepy, requests, flask

📜 License
MIT License

🎬 Created for fun, reels, and rapid meme delivery!

yaml
Copy
Edit

---

Let me know if you want a `render.yaml` or deployment screenshot too.