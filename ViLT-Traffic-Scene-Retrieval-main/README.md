# Traffic Scene Retrieval and Analysis using ViLT + RAG

## Overview

This project implements a Retrieval-Augmented Generation (RAG) pipeline for traffic scene understanding using the BDD100K dataset and ViLT (Vision-and-Language Transformer).

## Dataset

- Dataset: BDD100K
- Images Processed: 500+
- Embedding Size: 768
- Retrieval Method: Cosine Similarity
- Model: ViLT (Vision-and-Language Transformer)

## Features

- ViLT-based image embeddings
- Similar scene retrieval using cosine similarity
- Traffic scene analysis
- Dynamic scene description generation
- BDD100K dataset integration

## Tech Stack

- Python
- ViLT
- PyTorch
- Transformers
- Scikit-Learn
- Matplotlib
- BDD100K

## Workflow

1. Load BDD100K images and labels
2. Extract ViLT embeddings
3. Build retrieval database
4. Retrieve similar scenes
5. Generate contextual scene descriptions

## Results

The system retrieves visually similar traffic scenes and generates contextual descriptions based on detected objects and traffic conditions.

## Sample Output
<p align="center">
  <em>Traffic Scene Retrieval and Analysis using ViLT + RAG</em>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/a2091fe8-cc1f-4a4c-9284-a42424e12a03" width="850">
</p>

## Future Improvements

- Fine-tune ViLT on traffic scene datasets
- Integrate FAISS for large-scale retrieval
- Add real-time video scene retrieval
- Generate richer natural language scene summaries
- Deploy as a web application
