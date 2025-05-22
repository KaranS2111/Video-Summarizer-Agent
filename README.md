
# 🎥 Video AI Summarizer Agent

An AI-powered Streamlit web app that summarizes uploaded videos and provides intelligent responses to user queries using **Gemini 1.5 Flash** and **DuckDuckGo**. The app employs a multimodal AI agent from Phidata to analyze video content, gather supplementary web context, and deliver actionable insights.

---

## 🚀 Features

- Upload `.mp4`, `.mov`, or `.avi` video files
- Ask natural language queries about video content
- AI agent uses Gemini 1.5 Flash and DuckDuckGo for answers
- Displays summarized insights in a user-friendly format

---

## 🧠 Tech Stack

- **Streamlit** – UI
- **Phidata** – AI agent framework
- **Google Gemini 1.5 Flash** – Multimodal large language model
- **DuckDuckGo Tool** – For contextual web search
- **Google Generative AI SDK** – File handling and AI config

---

## 🔧 Installation

1. **Clone the repository**

    ```bash
    git clone https://github.com/yourusername/video-ai-summarizer.git
    cd video-ai-summarizer
    ```

2. **Create a virtual environment** (recommended)

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**

    ```bash
    pip install -r requirements.txt
    ```

4. **Set up environment variables**

    Create a `.env` file in the root directory with your Google API Key:

    ```env
    GOOGLE_API_KEY=your_google_api_key_here
    ```

5. **Run the application**

    ```bash
    streamlit run app.py
    ```

---

## 📁 File Structure

```
.
├── app.py               # Main Streamlit app
├── requirements.txt     # Python dependencies
├── .env                 # API key (not shared publicly)
└── README.md            # Project documentation
```

---

## 🧪 How It Works

1. User uploads a video file.
2. Video is uploaded and processed via Google Generative AI SDK.
3. User submits a query about the video.
4. The AI agent generates a context-aware response using:
   - Gemini 1.5 Flash (multimodal reasoning)
   - DuckDuckGo (for real-time web insights)
5. Response is displayed to the user.

---

## 📌 Notes

- Ensure you have a valid **Google API Key** with access to Gemini Flash.
- AI performance may vary based on video complexity and query specificity.

---

## 📄 License

MIT License © 2025 Your Name
