# 📺 YouTube Video Summarizer
A Python-based tool to summarize YouTube videos using the YouTube Transcript API and Hugging Face Transformers. This Colab-friendly notebook supports multiple languages, auto-chunks lengthy transcripts, and provides downloadable summaries for easy reading. Ideal for quick comprehension of long educational or informative videos.


🔗 **[Open in Google Colab](https://colab.research.google.com/drive/1INuMkIRm5JCt_bQ9R5Oul0RVx80wvG-l)**

---

## 🚀 Features

- 🔍 Extracts transcripts from YouTube videos
- 🧠 Generates concise and readable summaries
- 🌐 Supports multiple languages (English, Marathi, etc.)
- 💾 Option to save summary as a text file
- 📏 Automatically handles long transcripts by splitting into chunks
- ⚙️ 100% Colab-based, no local setup needed

---

## 🧪 Technologies Used

- Python
- Hugging Face Transformers (`pipeline`, `summarization`)
- YouTube Transcript API
- Google Colab

---

## 📋 Example Commands

| Action               | Description                              |
|----------------------|------------------------------------------|
| YouTube URL input    | Extracts transcript using video ID       |
| Language support     | Transcribes English or Marathi content   |
| Auto chunking        | Handles large transcript text            |
| Text summarization   | Uses Transformer models for summaries    |
| Save to file         | Exports output to `summarized_text.txt`  |

---

## 🔧 How It Works

1. Provide a YouTube video URL  
2. Extract the video ID from the URL  
3. Fetch the transcript using `YouTubeTranscriptApi`  
4. Merge transcript text into one string  
5. Use `transformers.pipeline("summarization")` to summarize the text  
6. Save the summarized output to a text file  

---

## 📂 File Output

