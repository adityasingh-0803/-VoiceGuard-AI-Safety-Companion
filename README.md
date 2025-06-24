# 🛡️ VoiceGuard: AI Safety Companion

**VoiceGuard** is a multilingual, voice-powered AI chatbot designed to support individuals—especially women—facing domestic violence or crisis situations. It enables users to speak in their native language and receive immediate, actionable support including legal aid, helplines, and safety resources.

> 🎤 Speak. 🧠 Get Help. 🌐 In Any Language.

---

## 🌍 About the Project

Millions of people—particularly women—face safety challenges but are unable to access help due to language barriers, fear, or technological limitations. **VoiceGuard** is designed to be a voice-first, inclusive, AI-powered chatbot that breaks these barriers through multilingual understanding, instant translation, and offline speech feedback.

---

## 🎯 Key Features

- 🎙️ **Voice Input** (Mic support)
- 🌐 **Multilingual Translation** (Using `deep_translator`)
- 🧠 **Intent Detection** (Help, Safety, Law)
- ⚖️ **Legal Information + Helplines**
- 🔊 **Offline Text-to-Speech Responses**
- 💬 **Gradio UI** for Web-Based Use

---

## 🚀 Run the Notebook

### 📥 Clone and Install
```bash
git clone https://github.com/YOUR_USERNAME/voiceguard-ai-safety-companion.git
cd voiceguard-ai-safety-companion
pip install -r requirements.txt
```
## ▶️ Launch in Notebook
Use Jupyter or Google Colab to run:
```bash
Multilingual Voice Safety Chatbot.ipynb
```
## 🧠 Tech Stack
Python 3

Gradio – Chat interface

SpeechRecognition – Voice-to-text

deep_translator – Translation (Google)

pyttsx3 – Text-to-speech

Pyaudio – Mic support

## 📊 Example Interactions
| Language | Input                       | Intent | Bot Response                                                 |
| -------- | --------------------------- | ------ | ------------------------------------------------------------ |
| Hindi    | मुझे मदद चाहिए              | Help   | 📞 Please call 181 or 100                                    |
| Bengali  | আমার নিরাপত্তা দরকার        | Safety | 🔒 Visit: [https://www.ncw.nic.in/](https://www.ncw.nic.in/) |
| Tamil    | சட்ட உதவி எங்கே கிடைக்கும்? | Law    | ⚖️ Section 498A IPC protects you                             |

## 💡 Hackathon Fit
🎯 Submitted for: AITHON – AI for Social Good Hackathon

VoiceGuard aligns with the Community & Safety, Inclusion & Equity, and Ethical AI goals by enabling accessible, real-world AI-powered support.

## 🔮 What's Next?
📱 Mobile-friendly PWA version

📡 Emergency alert integration (SMS/WhatsApp)

🤖 Smarter AI with HuggingFace intent classification

🧾 Conversation history with session memory

## 📄 License
This project is licensed under the MIT License. See LICENSE for details.
