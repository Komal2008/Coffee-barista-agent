# ☕ Coffee Barista AI Agent

An AI-powered Coffee Barista Agent built using **Google Vertex AI**, **Firestore Vector Search**, and **Streamlit**. The application provides intelligent coffee recommendations by retrieving menu items from a live Firestore database using semantic search and vector embeddings.

---

## 🚀 Live Demo

🔗 https://coffee-barista-207396891825.asia-south1.run.app

---

## ✨ Features

- 🤖 AI-powered coffee recommendation chatbot
- 🔍 Semantic search using vector embeddings
- ☁️ Google Vertex AI (Gemini)
- 🗄️ Firestore live database integration
- 📚 Firestore Vector Search
- 💬 Natural language conversations
- ⚡ Interactive Streamlit interface
- 🚀 Deployed on Google Cloud Run

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| Python | Backend |
| Streamlit | Web Interface |
| Google Vertex AI | LLM & Embeddings |
| Firestore | Database |
| Firestore Vector Search | Semantic Retrieval |
| Google Cloud Run | Deployment |
| Google Cloud SDK | Cloud Services |

---


## 📂 Project Structure

```text
Coffee-barista-agent/
│── agent.py
│── app.py
│── menu.json
│── requirements.txt
│── seed.py
└── README.md
```

---
---
## 🔐 Environment & Authentication

The application requires Google Cloud authentication to access Vertex AI and Firestore services.

Make sure your Google Cloud project is configured with:

- Vertex AI API
- Firestore
- Cloud Run
- Required IAM permissions
- Google Cloud credentials

---

## 🏗️ System Architecture

```text
                    ┌──────────────────┐
                    │      User        │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │    Streamlit     │
                    │   Web Interface  │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │   AI Agent       │
                    │    agent.py      │
                    └────────┬─────────┘
                             │
                    Generate Embedding
                             │
                             ▼
                    ┌──────────────────┐
                    │ Firestore Vector │
                    │      Search      │
                    └────────┬─────────┘
                             │
                    Relevant Menu Items
                             │
                             ▼
                    ┌──────────────────┐
                    │   Vertex AI      │
                    │     Gemini       │
                    └────────┬─────────┘
                             │
                             ▼
                    ┌──────────────────┐
                    │ AI Recommendation│
                    └──────────────────┘
```
---

## 🚀 Deployment

The application is deployed on **Google Cloud Run**.

### Deployment Flow

```text
Python Application
       ↓
Google Cloud Build
       ↓
Container Image
       ↓
Google Cloud Run
       ↓
Live Application
```
---


## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/Komal2008/Coffee-barista-agent.git
cd Coffee-barista-agent
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
streamlit run app.py
```

---

## ☁️ Google Cloud Services Used

- Vertex AI
- Firestore
- Firestore Vector Search
- Cloud Run
- IAM
- Cloud Shell

---

## 🧠 How It Works

1. User asks a coffee-related question.
2. The query is converted into vector embeddings.
3. Firestore Vector Search retrieves the most relevant menu items.
4. Vertex AI generates a context-aware response.
5. Streamlit displays the answer to the user.

---

## 💬 Example Questions

- Do you have a matcha drink?
- Recommend a hot coffee.
- What drinks are dairy-free?
- Suggest something sweet.
- What is your best latte?

---

## 📸 Screenshots

> 

### Home Page 

<img width="1900" height="817" alt="image" src="https://github.com/user-attachments/assets/df3b0ddd-b8c2-4b4d-8181-319441ec2556" />

### Chatbot |
<img width="1906" height="819" alt="image" src="https://github.com/user-attachments/assets/052b4472-fdd9-4a1a-9344-020c57f316fd" />


---

## 📈 Future Improvements

- 🔐 User Authentication
- 🛒 Online Ordering
- 💳 Payment Integration
- 🎙️ Voice Assistant
- 🌍 Multi-language Support
- ❤️ Personalized Recommendations
- 📊 Analytics Dashboard

---

## 👩‍💻 Author

**Komal Pandey**

- GitHub: https://github.com/Komal2008

---

## 📄 License

This project is licensed for educational and learning purposes.

---
---

## 👩‍💻 Author

**Komal Pandey**

Computer Science Student | Full Stack Developer | AI & Agentic AI Enthusiast

🔗 GitHub: https://github.com/Komal2008

---

## ⭐ Support

If you found this project interesting, consider giving it a ⭐ on GitHub!

---

<div align="center">

### ☕ Built with Python, Vertex AI, Firestore & Google Cloud

**Turning coffee conversations into intelligent recommendations.**

</div>
