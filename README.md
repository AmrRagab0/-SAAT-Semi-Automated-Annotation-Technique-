# 🎥 **SAAT - Semi-Automated Annotation Technique**  
📌 **Project Name:** SAAT - Semi-Automated Annotation Technique  
🎯 **Goal:** Automate and speed up the process of annotating sports videos using speech-to-text and AI-powered action recognition.  

---

## 📜 **Overview**  
SAAT is a **semi-automated annotation pipeline** that extracts commentary from sports videos, converts speech to text, and generates annotations based on detected keywords or AI-driven models. This helps reduce manual effort in labeling match events for training AI models, analytics, or content creation.  

---

## 🛠️ **Workflow & How to Use**

1. **Scrape Matches**  
   - Use the `Scraping_for_matches.ipynb` notebook to scrape the matches you need. This notebook automates the process of downloading sports videos from various websites.

2. **Extract Audio**  
   - The system extracts the audio track (`.mp3`) from the video.

3. **Speech-to-Text Model**  
   - Converts commentary into transcribed text using Whisper, as implemented in the `Semi_automated_annotation_.ipynb` notebook. This step ensures accurate transcription of the audio commentary for further processing.

4. **Two Annotation Paths:**  
   - **🔍 LLM-Based Annotation**  
     - Use the `LLm_Commentary_Event_Extraction.ipynb` notebook to leverage any open-source LLM model, such as LLaMA.
     - Use closed LLMs like ChatGPT or DeepSeek, to extract events   from the commentary. This allows for flexible and powerful event detection using state-of-the-art language models.
   - **🗝️ Keyword-to-Action Mapping**  
     - Detects specific keywords (e.g., "goal," "foul") and maps them to predefined actions using the `Semi_automated_annotation_.ipynb` notebook. This method provides a straightforward approach to event annotation based on keyword detection.

5. **Annotations Output**  
   - The generated annotations are stored/exported for further processing.

🔗 **Temporal Annotation and Visualization Tool**  
   - For more advanced annotation and visualization, you can use the [Soccer Event Annotation Tool](https://github.com/ibrahimabdelaal/Soccer-event-annotation-tool).

---

## 📦 **Features**  
- ✅ **Automated Speech-to-Text Processing**  
- 🤖 **AI-Based Annotation Generation**  
- 🔑 **Keyword-Based Event Detection**  
- ⚡ **Faster Video Annotation Process**  
- 🎙️ **Supports Sports Commentary Processing**  

---

## 🛠️ **Tech Stack**  
- **🐍 Python** – Main programming language  
- **🗣️ Whisper/OpenAI Speech-to-Text** – For transcription  
- **🎞️ FFmpeg** – For extracting audio from video  
- **🧠 LLM (GPT, etc.)** – For AI-based annotation  
- **🔍 Keyword Matching Algorithms** – For predefined action detection  

---

## 👥 **Contributors**  
- Amr Ragab  
- Ibrahim Salah
