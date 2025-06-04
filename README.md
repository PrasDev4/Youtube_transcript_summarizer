# YouTube Transcript Summarizer

[![GitHub stars](https://img.shields.io/github/stars/PrasDev4/Youtube_transcript_summarizer?style=social)](https://github.com/PrasDev4/Youtube_transcript_summarizer/stargazers)

A Python-based application that automatically fetches YouTube video transcripts and generates concise summaries — perfect for quick understanding of video content without watching the whole video!

---

## 🚀 Features

- Extracts video transcripts using YouTube APIs or available subtitles.
- Summarizes long transcripts using advanced natural language processing techniques.
- Supports videos with auto-generated or manual captions.
- Fast and efficient text summarization with transformer models or Google Gemini API.
- User-friendly interface (CLI or GUI options can be added).
- Saves summaries for offline reading or sharing.

---

## 📈 Why This Project?

Watching long videos can be time-consuming. This tool helps users save time by reading summaries of video transcripts, useful for students, researchers, content creators, and anyone looking to grasp video content quickly.

---

## 🛠️ Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/PrasDev4/Youtube_transcript_summarizer.git
    cd Youtube_transcript_summarizer
    ```

2. Create and activate a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. (Optional) If using Google Gemini API or any other API, set up your credentials as per instructions.

---

## ⚙️ Usage

Run the script with a YouTube video URL as input:
```bash
python main.py --url "https://www.youtube.com/watch?v=VIDEO_ID"
