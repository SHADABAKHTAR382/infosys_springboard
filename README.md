 <?xml version="1.0" encoding="utf-8"?>
<svg xmlns="http://www.w3.org/2000/svg"
     width="900" height="140" viewBox="0 0 900 140" role="img" aria-label="insfosys springboard">
  <!-- Dark Background -->
  <rect x="0" y="0" width="100%" height="100%" rx="12" fill="#0b1220" />
  
  <!-- Bold & Big Centered Text -->
  <text x="50%" y="50%" dominant-baseline="middle" text-anchor="middle"
        font-family="Arial, Helvetica, sans-serif"
        font-size="42" font-weight="bold" fill="#ffffff">
    insfosys_ springboard_6.0
  </text>
</svg>
![insfosys springboard dark box](./insfosys_springboard_6.0.svg)
- **code/** – contains the Google Colab / Jupyter notebook with the full pipeline.  

🎯 Objectives

- Prepare *10+ code snippets*.
- Parse each snippet with *AST (Abstract Syntax Tree)* to extract:
  - Functions
  - Classes
  - Imports
  - Code patterns  
- Tokenize each snippet.  
- Forward processed snippets to *three pretrained models*:
  - MiniLM
  - DistilRoBERTa
  - MPNet
- Perform *model comparisons* and generate *visualizations* to show differences in outputs/embeddings.

🛠 Methodology

1. *Collect Snippets*  
   A list of 10 small Python code snippets was prepared and stored in a list in the notebook.

2. *Parse with AST*  
   Used Python’s built-in ast module to walk through each snippet and extract:
   - Function names
   - Class names
   - Imported modules  

3. *Tokenize Code*  
   Simple regex-based tokenization to split code into tokens.

4. *Generate Embeddings*  
   Used Hugging Face sentence-transformers models:
   - all-MiniLM-L6-v2
   - paraphrase-distilroberta-base-v1
   - all-mpnet-base-v2
   
   SentenceTransformer.encode() was used to generate vector embeddings for each snippet.

5. *Compare Models*  
   Calculated cosine similarity between models for each snippet.  
   Used matplotlib to plot bar graphs showing similarity scores.



 🔧 How to Run

1. Open the notebook in *Google Colab*:  
   [Open in Colab](<https://colab.research.google.com/drive/1tCMmBQy5hooJP17mIzUTqd1-Y6F9Uv_8?usp=sharing>)

2. Run the cells step by step:
   - Install dependencies
   - Load code snippets
   - Parse, tokenize, and embed
   - View graphs and observations

3. All outputs (functions/classes/imports and visualizations) will appear below each cell.


 📝 Observations

- MiniLM and MPNet produced embeddings with higher mutual similarity compared to DistilRoBERTa for these Python snippets.
- The AST parsing successfully identified functions, classes, and imports for all snippets.
- Visualizations clearly show model differences across snippets.

(You can replace this section with your actual findings once you run the notebook.)



🧑‍💻 Author
Shadab Akhtar – shadabakhtar382@gmail.com


## 📜 License

This project is for educational purposes under Infosys Springboard 6.0.
