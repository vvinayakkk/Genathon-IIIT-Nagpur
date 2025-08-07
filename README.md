# 📞 AI-Powered Call Analysis Suite 🚀

![React Native](https://img.shields.io/badge/Mobile-React%20Native-blue) ![Docker](https://img.shields.io/badge/Containerized-Docker-orange) ![NLP](https://img.shields.io/badge/NLP-Advanced-red) ![IPFS](https://img.shields.io/badge/Storage-IPFS-green) ![Winner](https://img.shields.io/badge/Genathon-1st%20Place-gold)

## 🏆 **Gen-a-thon 2.0 Winning Project**
This AI-powered telecalling analysis system is designed to revolutionize enterprise call monitoring with real-time transcription, emotion detection, multilingual translation, and in-depth analytics. We developed **every feature with absolute precision**, leading us to **first place** in Gen-a-thon 2.0! 🎉
<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/43a1ec0b-c9f0-448e-b879-04589fb2f91a" />


---
## 📌 **Core Features**
### 📱 **Native Mobile Application (React Native)**
- ✅ **Call Log Collection**: Capture call duration, timestamps, contacts.
- ✅ **Call Recording**: Automatic recording of all calls.
- ✅ **Secure Upload**: Data securely stored in **IPFS & cloud**.
- ✅ **Optimized Performance**: Runs in the background **without draining battery**.

```mermaid
flowchart TD
  A[Incoming/Outgoing Call] -->|Capture Details| B(Call Log Storage)
  A -->|Record Audio| C(Call Recording)
  C -->|Upload to IPFS| D[Secure Storage]
```

### 🖥️ **Web-Based Admin Panel**
- 📊 **Dashboard**: Insights on total calls, call durations, and trends.
- 🎙️ **Call Playback**: Listen to recorded calls within the panel.
- 🔍 **Filters**: Sort by **date, employee, call type (incoming/outgoing)**.
- 📥 **Export Data**: Download logs & transcripts in **CSV, JSON**.
- 🔒 **Role-Based Access Control**: Secure access for managers & supervisors.

```mermaid
graph TD;
  A[Admin Panel] --> B[Dashboard: Call Stats];
  A --> C[Playback Call Recordings];
  A --> D[Filter & Sort Call Logs];
  A --> E[Export Data to CSV/JSON];
```

### 🧠 **AI-Powered NLP Engine**
- 🎤 **Speech-to-Text**: Converts call audio into accurate transcripts.
- 📝 **Summary Generation**: AI extracts key points automatically.
- 😊 **Sentiment & Emotion Analysis**: Captures tone, intent & emotional weight.
- 🌍 **Multilingual Support**: Translates transcripts in real time.
- 🔬 **5 Deep NLP Models** for enhanced analytics.

```mermaid
sequenceDiagram
  participant Call
  participant ASR as Speech-to-Text
  participant NLP as AI Processing
  participant AdminPanel

  Call->>ASR: Convert Audio to Text
  ASR->>NLP: Analyze Sentiment & Tone
  NLP->>AdminPanel: Display Summary & Insights
```

### 🐳 **Infrastructure & Deployment**
- 🚀 **Dockerized Services**: Easy-to-deploy containerized setup.
- 🔗 **IPFS for Secure Storage**: Decentralized and tamper-proof.
- 📡 **Real-time Sync**: Instant updates from mobile to admin panel.

```mermaid
graph TD;
  A[Docker Containers] -->|Mobile App| B[React Native];
  A -->|NLP Engine| C[FastAPI Backend];
  A -->|Database| D[PostgreSQL & IPFS];
```

---
## 🚀 **Tech Stack**
| Component         | Technology        |
|-----------------|-----------------|
| **Mobile App**  | React Native     |
| **Backend**     | FastAPI, Python  |
| **Database**    | PostgreSQL, IPFS |
| **NLP Models**  | Transformers, BERT, Whisper, Custom Models |
| **Deployment**  | Docker, Kubernetes |
| **Frontend**    | React.js, Tailwind CSS |

---
## 🎯 **Business Use Case**
🔹 **Monitor & ensure compliance** in customer service & sales teams.  
🔹 **Improve conversation quality** with deep insights into calls.  
🔹 **Automate large-scale call analysis**, saving time & resources.  

```mermaid
pie
  title AI-Powered Call Insights
  "Policy Compliance" : 35
  "Sentiment Analysis" : 25
  "Call Quality Monitoring" : 40
```

---
## 🏅 **Achievements & Why We Won 🏆**
✅ **End-to-end automation** with seamless call monitoring.  
✅ **5 AI models** capturing deep insights & emotions in calls.  
✅ **Multilingual NLP & real-time transcription**.  
✅ **Enterprise-ready, scalable & secure deployment**.  

```mermaid
stateDiagram-v2
  [*] --> Concept
  Concept --> Development
  Development --> AIIntegration
  AIIntegration --> Deployment
  Deployment --> 🎉 Victory!
```

🔹 **This project is more than just a call analysis tool—it’s a game changer for industries relying on telecommunication!**  

---
## 🚀 **Getting Started**
### 📦 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/yourrepo/ai-call-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd ai-call-analysis
   ```
3. Install dependencies:
   ```bash
   npm install   # for mobile app
   pip install -r backend/requirements.txt   # for backend
   ```
4. Start the services:
   ```bash
   docker-compose up --build
   ```

### ⚡ **Contributors**
👨‍💻 **Team AI Titans**  
- 🚀 **Vinayak & Team** - NLP, AI Models, Backend, DevOps  
- 📱 **Mobile Wizards** - React Native & Cloud Storage  
- 🎨 **Frontend Gurus** - Web Dashboard UI/UX  

---
## 📜 **License**
MIT License. Feel free to fork, modify, and contribute!

🔥 **Revolutionizing Call Analytics with AI!**

