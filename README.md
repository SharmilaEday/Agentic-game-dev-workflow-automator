# Agentic-game-dev-workflow-automator

# 🎮 Local Agentic Game Dev Assistant (Hugging Face)

This project is an **Agentic AI assistant** designed for game developers. It combines **Wikipedia search** with a **local Hugging Face LLM** (`flan-t5-base`) to automate creative game development tasks—entirely offline and open-source.

---

## 🚀 Features

- ✅ **Offline Text Generation** using Hugging Face Transformers
- 🔍 **Wikipedia Tooling** to gather world knowledge
- 🧠 **Agent-like Prompting** to enrich responses
- 🖥️ **Gradio UI** for simple, real-time interaction
- 📦 **No API key required** – works out-of-the-box

---

## 🏗️ How It Works

1. **Input Prompt** – The user enters a creative task (e.g., "Describe a robot hero in a dystopian world").
2. **Wikipedia Context** – The assistant retrieves 1–2 sentence background from Wikipedia.
3. **Local Model** – A prompt is constructed and passed to `flan-t5-base` for generation.
4. **Output** – A fluent, relevant answer is returned in real-time.

---

## 🧰 Tech Stack

- Python 3.10+
- [🤗 Transformers](https://huggingface.co/transformers/)
- [Gradio](https://gradio.app/)
- [Wikipedia](https://pypi.org/project/wikipedia/) Python API

---

## 💾 Installation

```bash
git clone https://github.com/yourusername/local-agentic-game-assistant.git
cd local-agentic-game-assistant
pip install -r requirements.txt
python app.py
