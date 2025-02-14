# **SAAT - Semi-Automated Annotation Technique**  
📌 **Project Name:** SAAT - Semi-Automated Annotation Technique  
🎯 **Goal:** Automate and speed up the process of annotating sports videos using speech-to-text and AI-powered action recognition.  

---

## **📜 Overview**  
SAAT is a **semi-automated annotation pipeline** that extracts commentary from sports videos, converts speech to text, and generates annotations based on detected keywords or AI-driven models. This helps reduce manual effort in labeling match events for training AI models, analytics, or content creation.  

---

## **🛠️ Workflow**  
1️⃣ **Match Video Input** – A match video is provided as input.  
2️⃣ **Extract Audio** – The system extracts the audio track (`.mp3`) from the video.  
3️⃣ **Speech-to-Text Model** – Converts commentary into transcribed text.  
4️⃣ **Two Annotation Paths:**  
   - **LLM-Based Annotation** – Uses a large language model (LLM) to generate annotations based on context.  
   - **Keyword-to-Action Mapping** – Detects specific keywords (e.g., "goal," "foul") and maps them to predefined actions.  
5️⃣ **Annotations Output** – The generated annotations are stored/exported for further processing.  

🔗 **Temporal Annotation and Visualization Tool** – For more advanced annotation and visualization, you can use the [Soccer Event Annotation Tool](https://github.com/ibrahimabdelaal/Soccer-event-annotation-tool).

---

## **📦 Features**  
✅ **Automated Speech-to-Text Processing**  
✅ **AI-Based Annotation Generation**  
✅ **Keyword-Based Event Detection**  
✅ **Faster Video Annotation Process**  
✅ **Supports Sports Commentary Processing**  

---

## **🛠️ Tech Stack**  
- **Python** – Main programming language  
- **Whisper/OpenAI Speech-to-Text** – For transcription  
- **FFmpeg** – For extracting audio from video  
- **LLM (GPT, etc.)** – For AI-based annotation  
- **Keyword Matching Algorithms** – For predefined action detection  


## **Contributers**
- Amr Ragab
- Ibrahim Salah
