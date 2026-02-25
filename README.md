# RAG-from-Scratch

Here is a weekend project about RAG (Retrieval-Augmented Generation) from scratch. I will implement a RAG workflow step to step via Jupyter Notebook. You can create a local "search engine" to find knowledge.

## Project Structure 

Until now, the structure of project like below:

- `pdfs`: I prepare some notes and blogs for you to test.
-  `RAG from scratch.ipynb`: In this notebook, you wil know:
  - How to deal with PDFs, such as OCR;
  - How to get the categories of a PDF files; 
  - How to use [Ollama]([Ollama](https://ollama.com/)) and [embeddinggemma](https://ollama.com/library/embeddinggemma) to embed text to vector, save and load them;
  - How to use embedded vectors, like calculating similarity between 2 vectors. 
  - How to find related text and ask LLM with them.



## To-Dos

1. Finish auto-process all files in `pdfs`;
2. Write a single Python script to show it;
3. Write C++ version.
