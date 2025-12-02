# 🧠 AI-Powered PPT Generator  
### Using Streamlit + n8n + Gemini API | Automated PowerPoint Creation 🚀

Generate PowerPoint presentations **automatically** using Artificial Intelligence!  
This project connects **Streamlit UI** ➝ **n8n automation** ➝ **Gemini API** ➝ **Python PPT Generator** to create slides from a simple text prompt.

---

## 🎥 Live Demo

▶ Watch Full Video: https://youtu.be/1vnrkm2o8Qo

---

## 🖼️ Workflow Snapshot

Below is a view of the n8n workflow used in this project:

<img width="1920" height="838" alt="AI-Powered PPT Generator Using Streamlit + n8n + Gemini API" src="https://github.com/user-attachments/assets/a7ca6713-1943-4453-ba55-85a0434ca546" />

---

## 🚀 Features

- ✨ AI-generated PPT slide content
- 🔗 Fully automated via **n8n Webhook**
- 🤖 Gemini API for slide text generation
- 🎛️ Streamlit interface for user input
- ⚙️ Background automation workflow
- 📥 Download final PPT instantly
- 🪄 Perfect for automation & AI mini-projects

---

## 🏗️ System Architecture

```text
User Prompt (Streamlit UI)
        ⬇
Webhook Trigger (n8n)
        ⬇
Gemini API (Generate PPT Content)
        ⬇
Python Script (Create PPTX File)
        ⬇
Return Download Link to User
````

---

## 🛠️ Tech Stack

| Component     | Technology Used          |
| ------------- | ------------------------ |
| Frontend      | Streamlit                |
| Automation    | n8n                      |
| AI Model      | Gemini API               |
| PPT Creation  | python-pptx              |
| Communication | Webhooks / HTTP Requests |

---

## 📦 Installation & Setup

### 1️⃣ Clone the Repo

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2️⃣ Install Python Libraries

```bash
pip install -r requirements.txt
```

### 3️⃣ Update API Keys in `streamlit_app.py`

```python
GEMINI_API_KEY = "your_key_here"
WEBHOOK_URL = "your_n8n_webhook"
```

### 4️⃣ Run Streamlit App

```bash
streamlit run streamlit_app.py
```

---

## ⚙️ n8n Setup

* Create a **Webhook Trigger**
* Add:

  * **HTTP Request** node (Gemini API)
  * **Python Function** node (Generate PPT)
  * **Respond to Webhook** node (Return File)
* Deploy workflow

---

## 📂 Project Structure

```
├── streamlit_app.py
├── generate_ppt.py
├── requirements.txt
└── README.md
```

---

## 📌 Future Enhancements

* 🔹 Custom themes & visuals
* 🔹 Add images inside slides
* 🔹 Multi-page structured presentations
* 🔹 Deployment on Cloud servers

---

## 📞 Connect With Me

💼 LinkedIn: [www.linkedin.com/in/shamanthula-bhavana-7343bb331]

---

