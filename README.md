 # CodeGenie — AI Explainer & Code Generator

*🚀 CodeGenie — AI Explainer & Code Generator
🏆 Milestone 1 — Static Analysis & Multi-Model Explainers

🎓 Program: Infosys Virtual Springboard Internship 6.0

🔍 Project Overview

CodeGenie is an AI-powered assistant built to explain and eventually generate code with deep, project-level understanding. Unlike standard code assistants, CodeGenie analyzes a developer’s unique codebase through AST parsing, token analysis, and NLP-based embeddings, enabling smarter, context-aware code explanations.

Milestone 1 serves as the foundation — demonstrating how to parse, analyze, and explain Python snippets using both rule-based logic and transformer-based AI models.

🎯 Objectives

✅ Parse 10+ Python snippets using AST (Abstract Syntax Tree)
✅ Extract functions, classes, imports, and patterns
✅ Perform tokenization and analyze keyword/operator frequency
✅ Generate embeddings using 3 pretrained NLP models:
• MiniLM (all-MiniLM-L6-v2)
• DistilRoBERTa (paraphrase-distilroberta-base-v1)
• MPNet (all-mpnet-base-v2)
✅ Compare model outputs & visualize similarities via PCA and bar charts

🧩 Methodology

Static Code Parsing — Extract structure (functions, classes, imports) using Python’s ast module.

Tokenization & Pattern Analysis — Identify keywords, operators, and token categories.

Rule-Based Explanations — Generate plain-English line-by-line code explanations.

NLP Model Explainers — Use SentenceTransformer models for deep contextual analysis.

Visualizations — Create bar charts, pie charts, word clouds, and PCA scatterplots to reveal insights.

🧠 Key Observations

✨ MiniLM and MPNet produced higher similarity in embeddings compared to DistilRoBERTa.
✨ AST parsing accurately identified all structural elements in the code.
✨ Visualizations revealed semantic clustering among functionally similar snippets.
✨ Combined static + semantic analysis proved effective for intelligent code understanding.

⚙️ How to Run

📍 Install required libraries: sentence-transformers, scikit-learn, pandas, matplotlib, nltk, etc.
📍 Open the Jupyter/Colab notebook Milestone_1.ipynb.
📍 Execute cells sequentially to generate all analysis reports and plots.

🧭 Roadmap

Milestone 2: Build a retrieval system and vector store.
Milestone 3: Integrate RAG for project-aware explanations.
Milestone 4: Develop an IDE plugin for interactive explain & generate workflows.

👨‍💻 Author & License

Author: Shadab Akhtar — Infosys Virtual Springboard Internship 6.0
Email: shadabakhtar382@gmail.com
License: Educational purpose under Infosys Springboard 6.0

💡 Summary

CodeGenie Milestone 1 successfully combines AST-based static analysis with transformer-powered explanations, offering a visual and analytical foundation for building a truly context-aware AI code assistant.

## 🔍 Project Overview

**CodeGenie** is an AI-powered assistant that aims to explain and later generate code with deep, context-aware understanding of an entire project. Unlike general-purpose assistants, CodeGenie focuses on personalized analysis by integrating static code analysis with modern NLP models.

**Milestone 1** lays the groundwork — parsing, analyzing, and explaining Python code snippets through both rule-based and transformer-based methods.

---

## 🎯 Objectives

* Parse and analyze 10+ Python snippets using **AST** (Abstract Syntax Tree)
* Extract **functions, classes, imports, and code patterns**
* Tokenize snippets and analyze **keyword/operator frequency**
* Generate embeddings and explanations using three pretrained models:

  * MiniLM (`all-MiniLM-L6-v2`)
  * DistilRoBERTa (`paraphrase-distilroberta-base-v1`)
  * MPNet (`all-mpnet-base-v2`)
* Compare model outputs and visualize semantic similarities

---

## 🧩 Methodology

1. **Static Code Parsing:** Used Python’s `ast` module to extract structural details from snippets.
2. **Tokenization & Pattern Analysis:** Counted keywords, operators, and token types.
3. **Rule-Based Explanations:** Generated simple English explanations line by line.
4. **NLP Model Explainers:** Used SentenceTransformer models for deeper semantic insights.
5. **Visualizations:** Created bar charts, pie charts, and PCA scatterplots to show token distribution and model similarity.

---

## 🧠 Observations

* **MiniLM** and **MPNet** produced more consistent embeddings than **DistilRoBERTa**.
* **AST parsing** accurately detected all functions and imports across snippets.
* Visualizations revealed meaningful clusters among snippets performing similar tasks.
* The experiment validated the potential for combining static and semantic analysis for smarter AI code understanding.

---

## ⚙️ How to Run

* Install dependencies: `sentence-transformers`, `scikit-learn`, `pandas`, `matplotlib`, `nltk`, and others.
* Open the Jupyter/Colab notebook `Milestone_1.ipynb`.
* Execute all cells sequentially to reproduce the analysis, embeddings, and plots.

---

## 🧭 Roadmap

**Milestone 2:** Build a vector store and retrieval pipeline.
**Milestone 3:** Integrate RAG for project-aware explanations.
**Milestone 4:** Develop an IDE plugin for interactive explain & generate workflows.

---

## 👨‍💻 Author & License

**Author:** Shadab Akhtar — *Infosys Virtual Springboard Internship 6.0*
**Email:** [shadabakhtar382@gmail.com](mailto:shadabakhtar382@gmail.com)
**License:** Educational use under Infosys Springboard 6.0

---

**CodeGenie Milestone 1** successfully demonstrates the foundation for a context-aware AI code assistant, combining AST-based static analysis with transformer-powered explanations and meaningful code visualizations.
