# Multi-Modal RAG Pipeline

This project implements a **multi-modal retrieval-augmented generation (RAG) pipeline** that processes text and image data from the *Attention Is All You Need* paper into vector embeddings and supports context-aware retrieval for downstream question answering tasks.<br>

## Features

- Ingest and chunk multimodal data (text + figures from the paper)  <br>
- Embed chunks using OpenAI embeddings  <br>
- Store vectors in ChromaDB  <br>
- Perform retrieval-augmented generation for QA<br>

## Contents

- `multi_modal_rag.ipynb` — end-to-end pipeline notebook  
- `requirements.txt` — dependencies  
- `synthetic_questions.txt` — example queries  

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/saamm/multi-modal-rag-pipeline.git
   ```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the notebook to execute the multimodal RAG workflow.<br>

## Data Source
The primary data used in this project is derived from the research paper:<br>
Attention Is All You Need (Vaswani et al., 2017).<br>

## Notes
Intended for research and prototyping purposes.<br>
Demonstrates cross-modal retrieval using a single scientific document.<br>
