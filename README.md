<div align="center">

# 🤖Local AI Agent

This project is a Local AI Agent built using LangChain, Ollama, and Chroma as the vector database.
It runs entirely on your local machine — no external API calls — ensuring privacy, speed, and full control over your data.


[![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)](https://www.langchain.com/)
[![Chroma](https://img.shields.io/badge/Chroma-FF4C29?style=for-the-badge&logo=google-chrome&logoColor=white)](https://www.trychroma.com/)
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=llama&logoColor=white)](https://ollama.ai/)

</div>

## Features

Local LLM with Ollama – Run AI models locally without internet dependency.
LangChain Integration – Orchestrate prompts, memory, and tools for complex AI workflows.
Chroma Vector Database – Store and retrieve embeddings for efficient semantic search.
Privacy First – All data and inference remain on your device.
Customizable – Easily switch models or add tools.

### Installation

Clone the repo and install dependencies:

```bash
git clone https://github.com/code-place7/local-ai-agent.git
cd local-ai-agent

```

###  Create a Virtual Environment
python -m venv venv
source venv/bin/activate    # Mac/Linux
venv\Scripts\activate       # Windows

###  Install Dependencies
pip install -r requirements.txt

###  Install & Run Ollama
Download Ollama from: https://ollama.ai
Run your desired model:
ollama run llama2

### Usage
python main.py
The agent will load your chosen Ollama model.
You can chat, store context, and retrieve information using Chroma.

### EXAMPLES
User: Summarize this PDF about AI ethics.
Agent: The document discusses the ethical considerations in AI development...

## 🤝 Contributing

Pull requests are welcome!
For major changes, please open an issue first to discuss what you would like to change.

## 📞 Contact

Have questions or suggestions? Reach out to us:

- **Email**: monumandel3@gmail.com

---

<div align="center">
  
### ⭐ Star us on GitHub — it helps!
<p align="center">
 👨‍💻 Author
Monu Mandal 
</p>

</div>



