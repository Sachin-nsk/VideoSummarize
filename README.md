# VideoSummarize 

VideoSummarize is a powerful AI-powered tool that automatically generates concise summaries of your videos. Simply upload a video, and our agent will analyze the content, identify key moments, and provide you with a summary that you can read in a fraction of the time it would take to watch the entire video.

-----

## 🚀 Features

  * **AI-Powered Summarization** – Leverages the power of Google's Gemini 2.5 Pro to analyze video content and generate accurate summaries.
  * **Web Research Integration** – Uses DuckDuckGo to gather additional context and information related to the video's content.
  * **Easy to Use** – Simple and intuitive interface for uploading videos and generating summaries.
  * **Supports Multiple Formats** – Works with a variety of video formats, including MP4, MOV, and AVI.

-----

## 🛠️ Tech Stack

| Layer | Tools & Services |
| :--- | :--- |
| **Core Framework** | `streamlit` |
| **AI Integration** | `phidata`, `google-generativeai` |
| **Web Search** | `duckduckgo-search` |
| **Utilities** | `python-dotenv` |

-----

## ⚙️ Setup & Installation

### 1️⃣ Clone the repo

```bash
git clone https://github.com/Sachin-nsk/VideoSummarize.git
cd VideoSummarize
```

### 2️⃣ Install dependencies

```bash
pip install -r requirement.txt
```

### 3️⃣ Set environment variables

Create a `.env` file and add your Google API key:

```bash
GOOGLE_API_KEY=your_api_key
```

### 4️⃣ Start the app

```bash
streamlit run app.py
```

-----

## 🧑‍💻 Author

Sachin Kumar N
