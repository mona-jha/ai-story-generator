# 🖼️ AI Story Generator from Images

An AI-powered Streamlit web app that takes your images and transforms them into a creative, narrated story — complete with text-to-speech audio!

## ✨ Features

- 📸 Upload **1 to 10 images** to inspire the story
- 🎭 Choose from **7 story styles**: Comedy, Thriller, Fairy Tale, Sci-Fi, Mystery, Adventure, and Morale
- 🤖 Story generated using **Google Gemini 2.5 Flash Lite**
- 🔊 Automatic **text-to-speech narration** via gTTS
- 🇮🇳 Stories feature **Indian names, places, and characters**
- 📖 Special sections for Mystery (solution), Thriller (twist), and Morale stories

## 🚀 Getting Started

### Prerequisites

- Python 3.9+
- A [Google AI Studio](https://aistudio.google.com/) API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/YOUR_USERNAME/ai-story-generator.git
   cd ai-story-generator
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up your API key**
   ```bash
   cp .env.example .env
   ```
   Open `.env` and replace `your_google_api_key_here` with your actual Google API key.

4. **Run the app**
   ```bash
   streamlit run app.py
   ```

5. Open your browser at `http://localhost:8501`

## 🗂️ Project Structure

```
ai-story-generator/
├── app.py                  # Streamlit frontend
├── story_generator.py      # Gemini API & gTTS logic
├── requirements.txt        # Python dependencies
├── .env.example            # Environment variable template
├── .gitignore              # Files to exclude from Git
└── README.md               # This file
```

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Streamlit](https://streamlit.io/) | Web UI |
| [Google Gemini](https://ai.google.dev/) | Story generation |
| [gTTS](https://gtts.readthedocs.io/) | Text-to-speech narration |
| [Pillow](https://python-pillow.org/) | Image processing |

## 📋 Usage

1. Open the app in your browser
2. Use the **sidebar** to upload 1–10 images (PNG, JPG, JPEG)
3. Select your preferred **story style**
4. Click **"Generate Story and Narration"**
5. Read your story and listen to the audio narration!

## ⚙️ Environment Variables

| Variable | Description |
|----------|-------------|
| `GOOGLE_API_KEY` | Your Google AI Studio API key |

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
