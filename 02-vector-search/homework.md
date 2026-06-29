# Homework 2 – Vector Search

Source: [homework instructions](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/cohorts/2026/02-vector-search/homework.md)

## Solution

All questions are solved in a single notebook: [homework.ipynb](homework.ipynb)

Helper scripts (copied from the course repo):
- [download.py](download.py): fetches the ONNX model from HuggingFace
- [embedder.py](embedder.py): `Embedder` class wrapping the ONNX session

## How to run

1. Make sure the `llm-zoomcamp-2026` conda environment is active and has the required packages:
   ```bash
   pip install onnxruntime tokenizers huggingface-hub numpy minsearch gitsource
   ```

2. Download the ONNX model (one-time):
   ```bash
   cd 02-vector-search
   python download.py
   ```

3. Open and run [homework.ipynb](homework.ipynb) top to bottom.

## Answers

| # | Question | Answer |
|---|----------|--------|
| Q1 | First value of query embedding `v[0]` | **`-0.02`** |
| Q2 | Cosine similarity with `07-sqlitesearch-vector.md` | **`0.37`** |
| Q3 | Filename of highest-scoring chunk | **`02-vector-search/lessons/07-sqlitesearch-vector.md`** |
| Q4 | First result from `VectorSearch` | **`04-evaluation/lessons/05-search-metrics.md`** |
| Q5 | File in vector results but not text results | **`02-vector-search/lessons/08-pgvector.md`** |
| Q6 | First result after RRF hybrid search | **`01-agentic-rag/lessons/13-function-calling.md`** |

> Answers may vary slightly depending on library versions. Select the closest option.
