# 🧠 MindfulMate: A Compassionate Mental Health Chatbot

**MindfulMate** is a Streamlit-based AI-powered mental health chatbot built specifically for Indian users. It utilizes **Google’s Gemini 1.5 Flash** model to deliver warm, mood-aware, and emotionally intelligent conversations. The chatbot also features real-time **distress detection** and provides immediate access to verified **Indian mental health helplines**.

## 🌟 Features

- 💬 **Natural, flowing conversations** — feels like chatting with a supportive friend  
- 🧘 **Mood-based tone adjustment** — adapts responses based on selected mood  
- 🚨 **Distress detection** — responds to suicidal/self-harm cues with empathy and emergency helplines  
- 📱 **Session-based chat history** — no data storage; privacy-first interaction using Streamlit  
- 🇮🇳 **Localized support** — integrates Indian mental health helpline resources

## 🛠️ Installation

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/mindfulmate-chatbot.git
cd mindfulmate-chatbot
```

### 2. Install dependencies:
```bash
pip install -r requirements.txt
```

### 3. Add your Google Gemini API key:
- Open `chatbot.py` (or `app.py`)
- Replace the placeholder API key with your actual Google API key  
  *or*  
- Load your key securely using environment variables

### 4. Run the chatbot:
```bash
streamlit run chatbot.py
```

---

## 📦 Requirements

- Python 3.x  
- Streamlit  
- Google Generative AI SDK (`google-generativeai`)  

## 🙋‍♀️ Usage

1. Launch the chatbot in your browser  
2. Select your current mood  
3. Start chatting with **MindfulMate**  
4. Receive friendly, empathetic, and concise responses  
5. If distress is detected, MindfulMate will share relevant helpline numbers immediately

## 📞 Indian Mental Health Helplines

MindfulMate responds with these verified resources during signs of emotional distress:

- **Vandrevala Foundation**: 1860-2662-345 (24/7)  
- **iCall Helpline**: 9152987821 (10 AM – 8 PM)  
- **National Mental Health Helpline**: 080-46110007  
- **Emergency Services**: Dial 112

## ⚠️ Disclaimer

**MindfulMate** is intended as an AI-based emotional support tool. It is **not a replacement for professional mental health care**. In cases of serious mental health concerns, always consult a licensed therapist or medical professional.

