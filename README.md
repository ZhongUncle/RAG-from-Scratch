# RAG-from-Scratch

Here is a weekend project about RAG (Retrieval-Augmented Generation) from scratch. I will implement a RAG workflow step to step via Jupyter Notebook. You can create a local "search engine" to find knowledge.



## Model

I use [embeddinggemma](https://ollama.com/library/embeddinggemma), [GLM-OCR](https://ollama.com/library/glm-ocr), [GPT-OSS 20B](https://ollama.com/library/gpt-oss:20b). If your GPU can't run it, please change GPT-OSS 20B to Gemma3 12B or other LLM you can run (need supoort multi-languages). 

I use 3080 20GB (Yes, 3080 with 20GB VRAM). The peak VRAM usage is about 19GB.

## Project Structure 

Until now, the structure of project like below:

- `pdfs`: I prepare some notes and blogs for you to test.
-  `RAG from scratch.ipynb`: In this notebook, you wil know:
  - How to deal with PDFs, such as OCR;
  - How to get the categories of a PDF files; 
  - How to use [Ollama](https://ollama.com/) and [embeddinggemma](https://ollama.com/library/embeddinggemma) to embed text to vector, save and load them;
  - How to use embedded vectors, like calculating similarity between 2 vectors. 
  - How to find related text and ask LLM with them.



## To-Dos

1. Add some diagrams to illustrate;
2. Finish Version 2.0;
3. Write a single Python script to show it;
4. Write C++ version.
