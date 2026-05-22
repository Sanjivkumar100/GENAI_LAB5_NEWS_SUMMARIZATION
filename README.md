# GENAI_LAB5_TAMIL_NEWS_SUMMARIZATION
# LLM-Powered News Summarization with Text-to-Speech Using Gemini API

An AI-powered application that summarizes long news articles into concise summaries using the **Google Gemini API** and converts the generated summaries into speech using **Text-to-Speech (gTTS)** technology. 

---

# 📌 Project Overview

This project demonstrates the practical application of **Large Language Models (LLMs)** in automating news summarization and audio generation. The system takes lengthy news articles as input, processes them using the Gemini API, generates meaningful summaries, and converts the summarized text into speech output.

The application helps users quickly understand long articles while improving accessibility through audio playback. 

---

# 🎯 Objectives

* Automatically summarize lengthy news articles
* Reduce reading time for users
* Convert summarized text into audio
* Demonstrate real-world applications of LLMs
* Build a beginner-friendly AI application using Gemini API 

---

# 🛠️ Technologies Used

| Technology        | Purpose                   |
| ----------------- | ------------------------- |
| Python            | Programming Language      |
| Google Gemini API | LLM-based Summarization   |
| gTTS              | Text-to-Speech Conversion |
| Pandas            | Dataset Handling          |
| Google Colab      | Development Platform      |



---

# 📂 Dataset Used

### Dataset:

**Indian News 2024–2025 Summarization Dataset**

### Dataset Contains:

* News articles
* Corresponding summaries

The news articles are used as input for the LLM summarization process. 

---

# ⚙️ Working of the Project

The project workflow consists of the following steps:

---

## Step 1 — User Input

The user manually enters a news article or selects one from the dataset.

### Example:

```text id="v8i0mo"
Bollywood in 2025 has proven to be a dynamic mix...
```



---

## Step 2 — LLM Processing

The article is sent to the **Google Gemini API** with a summarization prompt.

### Example Prompt:

```python id="j8rvur"
Summarize the following news article in simple and short points
```

The Gemini model analyzes the article and generates a concise summary. 

---

## Step 3 — Summary Generation

The AI generates a shorter version of the article while preserving important information.

### Example Output:

```text id="i0rvga"
Bollywood in 2025 focused on emotional storytelling, patriotism,
and meaningful narratives across multiple genres.
```



---

## Step 4 — Text-to-Speech Conversion

The generated summary is converted into speech using the **gTTS library**. 

---

## Step 5 — Audio Output

The summarized speech is played for the user as audio output. 

---

# 🏗️ Project Workflow

```text id="uzzzn7"
User Input News Article
          ↓
Gemini API Processing
          ↓
LLM-based Summarization
          ↓
Summary Generation
          ↓
Text-to-Speech Conversion
          ↓
Audio Output
```

The diagrams in the document illustrate the flow of article input, LLM summarization, API interaction, and speech generation. 

---

# 📥 Input and Output

| Input             | Output                        |
| ----------------- | ----------------------------- |
| Long News Article | Short Summarized Text + Audio |



---

# ✨ Features

* Automatic Text Summarization
* AI-powered LLM Processing
* Text-to-Speech Conversion
* Supports Long Articles
* Beginner-Friendly Implementation
* Real-Time Summarization 

---

# 📈 Advantages

* Saves reading time
* Simplifies lengthy news articles
* Audio accessibility support
* Demonstrates modern AI technologies
* Useful for students and researchers 

---

# 🌍 Applications

* News Summarization
* Educational Content Summarization
* Research Paper Summarization
* Voice Assistants
* Accessibility Applications 

---

# 🔮 Future Enhancements

* Multi-language Support
* Speech-to-Text Input
* PDF Summarization
* Web Application Deployment
* Emotion-based Voice Generation 

---

# 🚀 Conclusion

This project successfully demonstrates how **Large Language Models (LLMs)** can be integrated with **Text-to-Speech technology** to create an intelligent news summarization system. By leveraging the **Google Gemini API**, the application provides fast, accurate, and user-friendly summarization with audio accessibility support, showcasing the real-world potential of AI-powered solutions. 

---

# 📚 Author

**Sanjiv Kumar**
B.Tech Information Technology
AI & Data Science Enthusiast
