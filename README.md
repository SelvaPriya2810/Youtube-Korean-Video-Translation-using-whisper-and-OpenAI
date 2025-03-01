

# **YouTube Korean Speech-to-Text and Translation** 🎙️🌍  

## **Overview**  
This project extracts **audio from YouTube videos**, converts **Korean speech to text**, and translates it to **English**. It leverages **yt-dlp** for audio extraction, **OpenAI Whisper** for speech recognition, and **GPT-4 Turbo** for translation.

## **Features**  
- 🎵 **Extracts YouTube audio** using `yt-dlp`.  
- 🎙 **Converts Korean speech to text** using **OpenAI Whisper**.  
- 🌍 **Translates Korean to English** using **GPT-4 Turbo**.  

## **Project Workflow**  
1. **Extract Audio** – Downloads and extracts **audio from a YouTube video** using `yt-dlp`.  
2. **Speech-to-Text** – Converts **Korean speech to text** using **OpenAI Whisper**.  
3. **Translation** – Translates **Korean text to English** using **GPT-4 Turbo**.  

## **Installation**  

### **1. Clone the Repository**  
```bash
git clone https://github.com/your-username/youtube-korean-speech-translation.git
cd youtube-korean-speech-translation
```

### **2. Install Dependencies**  
Ensure you have **Python 3.7+** installed, then install the required dependencies:  
```bash
pip install yt-dlp openai
```

### **3. Set Up API Key**  
- Obtain an **OpenAI API key** from [OpenAI](https://openai.com/) and set it up in your environment.  

### **4. Run the Project**  
Process a **YouTube video** and convert Korean speech to English translation:  
```bash
python main.py --url "https://www.youtube.com/watch?v=example"
```

## **Usage**  
- Extract **audio** from YouTube videos.  
- Convert **Korean speech to text** using **OpenAI Whisper**.  
- Translate **Korean text to English** using **GPT-4 Turbo**.  

## **Future Enhancements**  
- 📌 Add **text-to-speech conversion** for English translation output.  
- 🔍 Improve **translation accuracy** with custom GPT fine-tuning.  
- 🏗 Extend support for **multiple languages beyond Korean**.  


