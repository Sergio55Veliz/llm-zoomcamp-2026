# Homework 1 – Agentic RAG

Source: [homework instructions](https://github.com/DataTalksClub/llm-zoomcamp/blob/main/cohorts/2026/01-agentic-rag/homework.md)

## Solution

All questions are solved in a single notebook: [homework.ipynb](homework.ipynb)

## How to run

1. Make sure the `llm-zoomcamp-2026` conda environment is active and has the required packages:
   ```bash
   pip install gitsource minsearch openai python-dotenv
   ```

2. Create a `.env` file at the **project root** with your OpenAI key:
   ```
   OPENAI_KEY=abc-...
   ```

3. Open and run [homework.ipynb](homework.ipynb) top to bottom. The data is downloaded
   once in the Setup section and reused across all questions.

## Answers

| # | Question | Answer |
|---|----------|--------|
| Q1 | How many lesson pages? | **72** |
| Q2 | Filename of first search result | **`01-agentic-rag/lessons/14-agentic-loop.md`** |
| Q3 | Input tokens (full-page RAG) | **~7000** |
| Q4 | Number of chunks (size=2000, step=1000) | **295** |
| Q5 | Token reduction with chunking vs Q3 | **~3x fewer** |
| Q6 | Number of agent search calls | **~4** |

> Answers may vary slightly depending on the model run. I selected the closest option.
