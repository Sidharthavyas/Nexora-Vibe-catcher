Vibe Matcher – Mini Recommender System

AI Internship Assignment – Nexora
Author: Sidhartha Vyas

1. Overview

This repository contains a complete, fully functional implementation of a lightweight vibe-based product recommendation system.
The system uses local text embeddings and cosine similarity to match a user’s vibe query (e.g., “energetic urban chic”) to the most relevant fashion products.

All work is done in a single file, runs smoothly in Google Colab, and does not require any paid APIs.

2. Features Implemented

✅ 8-item fashion product catalog
✅ Local embeddings using sentence-transformers
✅ Cosine similarity vector search
✅ Top-3 ranked recommendations with similarity scores
✅ Evaluation on 3 test queries
✅ Good@1 metric (threshold ≥ 0.70)
✅ Latency measurement and bar chart
✅ Full output logging
✅ Reflection section included
✅ One-file, reproducible solution

3. Why OpenAI API Was Not Used

The assignment originally suggested using OpenAI embeddings.
However, this implementation does not use the OpenAI API for the following reasons:

Reason

I do not currently have active OpenAI credits, and embeddings require a funded account.
To ensure the project remains fully functional, reproducible, and free, I implemented the system using a local embedding model (all-MiniLM-L6-v2) which provides:

High-quality embeddings

No API keys needed

Zero cost

Full offline compatibility

Stable results suitable for vector search tasks

This approach meets all assignment requirements without depending on paid APIs.

4. Technology Stack

Python

Google Colab

Sentence Transformers (all-MiniLM-L6-v2)

scikit-learn

NumPy

Pandas

Matplotlib

All dependencies are free and installable with a single command.

5. How to Run
A. In Google Colab

Open a new notebook.

Install dependencies:

!pip install --quiet pandas numpy scikit-learn matplotlib sentence-transformers


Copy and paste the entire one-file code into a single cell.

Run all.

B. Local environment

Create a virtual environment.

Install the same dependencies.

Run the script normally.

6. Results Included

The notebook/script includes:

Product catalog

Embeddings

Top-3 matches per query

Evaluation table

Similarity scores

Latency plot

Reflection summary

All results appear when running the script top-to-bottom.

7. Reflection Summary

A vector database (Pinecone, Milvus) would improve scalability.

A cross-encoder re-ranker would improve ranking precision.

More detailed product labels would improve evaluation.

Caching would reduce latency.

Multilingual models could support non-English queries.

8. Why AI at Nexora

I am drawn to Nexora because its work focuses on building practical, human-centered intelligence into digital experiences. My strength lies in translating abstract user input into structured embeddings, retrieval pipelines, and measurable outputs. I enjoy prototyping quickly, evaluating iteratively, and improving systems through well-defined metrics. Nexora’s focus on intelligent discovery and personalization aligns closely with my technical interests and the way I approach building real-world AI features.
