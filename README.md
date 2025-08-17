# RAG (Retrieval-Augmented Generation) Playground

This repository contains experiments and code for working with Retrieval-Augmented Generation (RAG), vector embeddings, and document ingestion/parsing using Python and popular libraries such as LangChain, HuggingFace, FAISS, and ChromaDB.

## Features

- **Data Ingestion & Parsing:**  
  Notebooks and scripts for parsing and ingesting documents (PDF, DOCX, etc.) for downstream NLP tasks.

- **Vector Embeddings & Databases:**  
  Examples of generating vector embeddings for text using HuggingFace models and storing/querying them with vector databases like FAISS and ChromaDB.

- **Jupyter Notebooks:**  
  Interactive notebooks for step-by-step experimentation and visualization.

## Project Structure

```
.
├── main.py
├── requirements.txt
├── pyproject.toml
├── .env
├── .gitignore
├── data/
│   └── attention .pdf
├── DataIngestionParsing/
│   └── dataingestion.ipynb
├── VectorEmbeddingAndDatabases/
│   └── embedding.ipynb
```

- `main.py`: Entry point for running the project.
- `requirements.txt` / `pyproject.toml`: Python dependencies.
- `data/`: Example data files.
- `DataIngestionParsing/`: Notebooks for document ingestion and parsing.
- `VectorEmbeddingAndDatabases/`: Notebooks for embedding and vector database experiments.

## Setup

1. **Python Version:**  
   Requires Python 3.13 (see [.python-version](.python-version)).

2. **Install Dependencies:**  
   You can use pip or your preferred environment manager:
   ```sh
   pip install -r requirements.txt
   ```

3. **Environment Variables:**  
   Create a `.env` file for any required API keys or configuration.

4. **Run Notebooks:**  
   Open the notebooks in VS Code or Jupyter Lab and run the cells interactively.

5. **Run Main Script:**  
   ```sh
   python main.py
   ```

## Notebooks

- **Data Ingestion:**  
  See [`DataIngestionParsing/dataingestion.ipynb`](DataIngestionParsing/dataingestion.ipynb)

- **Vector Embedding & Visualization:**  
  See [`VectorEmbeddingAndDatabases/embedding.ipynb`](VectorEmbeddingAndDatabases/embedding.ipynb)

## Dependencies

Key libraries used:
- [LangChain](https://github.com/langchain-ai/langchain)
- [HuggingFace Transformers](https://huggingface.co/docs/transformers/index)
- [FAISS](https://github.com/facebookresearch/faiss)
- [ChromaDB](https://github.com/chroma-core/chroma)
- [Matplotlib](https://matplotlib.org/)
- [Pandas](https://pandas.pydata.org/)

See [`requirements.txt`](requirements.txt) and [`pyproject.toml`](pyproject.toml) for the full list.

## License

[MIT](LICENSE) (add a LICENSE file if you want to specify)

---

*This repo is a playground for learning and experimenting with RAG, embeddings, and vector databases. Contributions and suggestions are welcome!*
