# 🤖 AI Text Summarizer using T5 Transformer

An AI-powered Text Summarization web application built using FastAPI, Hugging Face Transformers, and PyTorch. The project uses a fine-tuned T5 Transformer model trained on a text summarization dataset to generate concise and meaningful summaries from long-form text.

## 🚀 Live Demo

🌐 https://shivarajbirajadar-text-summarizer.hf.space

## 📂 GitHub Repository

🔗 https://github.com/shivarajbirajadar/text-summarizer

---

## 📌 Project Overview

This project demonstrates the complete AI/ML workflow:

- Dataset preprocessing and cleaning
- Transformer model fine-tuning
- GPU-based model training
- Model evaluation and inference
- FastAPI backend development
- Docker containerization
- Cloud deployment on Hugging Face Spaces

The model is capable of generating abstractive summaries that capture the main meaning of long text while reducing unnecessary information.

---

## ✨ Features

- Abstractive text summarization
- Fine-tuned T5 Transformer model
- FastAPI REST API backend
- User-friendly web interface
- Real-time summary generation
- Dockerized deployment
- Hosted on Hugging Face Spaces

---

## 🧠 Machine Learning Pipeline

### 1. Data Collection

- Used a text summarization dataset
- Prepared training and validation data

### 2. Data Preprocessing

- Text cleaning
- Lowercasing
- Removing unwanted characters
- Tokenization

### 3. Model Training

- Fine-tuned T5 Transformer model
- Trained using Hugging Face Transformers
- Utilized Google Colab GPU resources for accelerated training

### 4. Model Deployment

- Saved trained model weights
- Integrated model with FastAPI
- Deployed using Docker and Hugging Face Spaces

---

## 🛠️ Tech Stack

### AI / ML

- Python
- PyTorch
- Hugging Face Transformers
- T5 Transformer
- NLP

### Backend

- FastAPI
- Uvicorn

### Deployment

- Docker
- Hugging Face Spaces

### Version Control

- Git
- GitHub
- Git LFS

---

## 📁 Project Structure

```bash
TEXTSUMMARY/
│
├── app.py
├── index.html
├── Dockerfile
├── requirements.txt
├── README.md
│
└── saved_summary_model/
    ├── config.json
    ├── generation_config.json
    ├── model.safetensors
    ├── tokenizer.json
    └── tokenizer_config.json
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/shivarajbirajadar/text-summarizer.git
cd text-summarizer
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
uvicorn app:app --reload
```

Open:

```text
http://127.0.0.1:8000
```

---

## 📊 Example

### Input

```text
Artificial Intelligence is transforming the way people interact with technology. Companies around the world are investing heavily in machine learning and deep learning research to create smarter applications.
```

### Output

```text
AI is transforming the way people interact with technology, and companies are investing heavily in machine learning and deep learning to create smarter applications.
```

---

## 🎯 Skills Demonstrated

- Machine Learning
- Deep Learning
- Natural Language Processing (NLP)
- Transformer Models
- Model Fine-Tuning
- FastAPI Development
- REST APIs
- Docker
- Cloud Deployment
- Git & GitHub

---

## 👨‍💻 Author

### Shivaraj Birajadar

- GitHub: https://github.com/shivarajbirajadar
- LinkedIn: https://www.linkedin.com/in/shivaraj-birajadar-a8a23a294

---

## ⭐ Future Improvements

- Support for multiple summarization models
- Batch document summarization
- PDF and DOCX upload support
- User authentication
- Summary quality evaluation metrics
- Model optimization for faster inference

---

## 📜 License

This project is developed for educational, research, and portfolio purposes.
