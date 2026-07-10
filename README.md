# 🧠 GenZify

> AI-powered text transformation tool built using **Python**, **Streamlit**, **LangChain**, **Ollama**, and a locally hosted **Llama 3.1 8B** model.

GenZify converts standard English into expressive **Gen Z / Brainrot** style text using prompt engineering and local Large Language Model inference. The entire application runs locally through Ollama without relying on external AI APIs.

---

## ✨ Features

- 🤖 Local AI inference using **Llama 3.1 8B**
- ⚡ No external API calls or API keys required
- 📝 Converts normal English into Gen Z / Brainrot style text
- 🧠 Prompt-engineered for expressive and context-aware outputs
- 💻 Interactive web interface built with Streamlit
- 🔒 Fully local execution through Ollama

---

## 🛠️ Tech Stack

- Python
- Streamlit
- LangChain
- Ollama
- Llama 3.1 8B

---

# 🚀 Getting Started

## Clone the repository

```bash
git clone https://github.com/Sanchit1612/GenZify.git

cd GenZify
```

## Install dependencies

```bash
pip install -r requirements.txt
```

## Install Ollama

Download Ollama from:

https://ollama.com/download

## Download the model

```bash
ollama pull llama3.1:8b
```

## Start Ollama

```bash
ollama serve
```

## Launch the application

```bash
streamlit run app.py
```

---

# 🧠 How It Works

1. User enters plain English text.
2. LangChain injects the input into a custom prompt template.
3. Ollama forwards the prompt to the locally hosted **Llama 3.1 8B** model.
4. The model generates a Gen Z / Brainrot version of the text.
5. Streamlit displays the generated response in real time.

---

# 💡 Example

### Input

```
I have an interview tomorrow.
```

### Output

```
BRO 😭💀 I GOT AN INTERVIEW 🔥 TOMORROW 😭🧠 NAHH IM COOKED 💀🔥 WISH ME LUCK FR 😭🤡
```

---

# 📂 Project Structure

```
GenZify
│
├── app.py
├── requirements.txt
└── README.md
```

---

# 📚 What I Learned

- Prompt Engineering
- LangChain Prompt Templates
- Local LLM Inference
- Running LLMs using Ollama
- Building AI applications with Streamlit
- Integrating Python with Large Language Models

---

# 🔮 Future Improvements

- Multiple writing styles
- Creativity / Temperature controls
- Chat history
- Export generated text
- Multi-model support (Gemma, Mistral, DeepSeek, etc.)
- Custom prompt presets

---

# 👨‍💻 Author

**Sanchit Goel**

- GitHub: https://github.com/Sanchit1612

---

## ⭐ If you found this project useful, consider giving it a star!
