# 📝 Text Summarization Web App

A simple Text Summarization project built using **T5-small (Transformers)** with a **FastAPI backend** and a basic **HTML frontend**.

---

## 🚀 Features

* Summarizes long text into concise output
* Powered by HuggingFace Transformers (T5-small)
* FastAPI backend for inference
* Simple HTML UI for interaction

---

## 🧠 Model

* Model: `t5-small`
* Framework: PyTorch
* Library: HuggingFace Transformers

---

## 🏗️ Project Structure

```
├── app/
│   ├── main.py          # FastAPI backend
│   ├── model/           # Saved model files
│
├── templates/
│   └── index.html       # Frontend UI
│
├── requirements.txt
├── README.md
└── .gitignore
```

---s

## ⚙️ Installation

```
git clone <https://github.com/Fahad9009/Text_Summarization_Web_App.git>
cd <repo-name>

pip install -r requirements.txt
```

---

## ▶️ Run the App

```
uvicorn app.main:app --reload
```

Open in browser:

```
http://127.0.0.1:8000
```

---

## 📦 API Endpoint

### POST `/summarize`

**Request:**

```
{
  "text": "Your long text here"
}
```

**Response:**

```
{
  "summary": "Summarized text"
}
```

---

## 🛠️ Tech Stack

* Python
* PyTorch
* Transformers (HuggingFace)
* FastAPI
* HTML/CSS


---

## Licence

MIT