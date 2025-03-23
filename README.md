# Nabafat LLM-Powered Book Generator

🚀 **Nabafat's AI-Powered Book Generator** is an advanced LangGraph-based agent designed to generate structured books chapter by chapter using the power of **Groq’s DeepSeek LLM**.

## 🌟 Features
- **Automated Book Generation**: Generates structured content with logical flow.
- **LangGraph Integration**: Ensures chapters build upon one another.
- **Powered by DeepSeek LLM**: High-performance AI text generation.
- **Scalable & Customizable**: Suitable for research, documentation, and storytelling.

## 📌 Installation
Ensure you have Python installed, then run:
```bash
pip install langgraph gradio langchain_openai langchain-groq
```

## 🚀 Usage
```python
from langgraph.graph import StateGraph
from langchain_groq import ChatGroq

# Initialize LLM
llm = ChatGroq(model="deepseek-r1-distill-llama-70b", temperature=0)

# Define book generation process using LangGraph
...
```

## 📖 How It Works
1. User inputs a query.
2. AI generates chapters in sequence.
3. Final structured content is outputted.

## 🤝 Contributing
We welcome contributions! Feel free to fork this repository and submit a pull request.

## 📜 License
This project is licensed under the MIT License.

---
**Follow Nabafat for more AI innovations!** 🚀

