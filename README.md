# Constitution of Sri Lanka RAG Model

This repository contains the resources for a **Retrieval-Augmented Generation (RAG)** model focused on the Constitution of Sri Lanka. The project leverages a pre-trained model with an information corpus of the constitution, enabling an interactive chatbot capable of answering queries based on constitutional law.

## Project Structure

- ### RAG Interface  
  Contains the primary interface for the deployed chatbot. This folder includes:
  - Jupyter notebooks for the model deployment process.
  - Scripts to convert the corpus into manageable chunks and generate embeddings.
  - FAISS index creation to enable efficient search and retrieval of relevant corpus information during interactions with the RAG model.

- ### Experimental Setup  
  Includes Jupyter notebooks with experimental configurations and trials using different models and parameters. The experiments are aimed at improving retrieval and response accuracy. Some experiments are incomplete, representing ongoing development and testing.

## Usage

- **Deployed Model**  
  The model is hosted on Hugging Face Spaces: [Constitution RAG](https://huggingface.co/spaces/AtleeBugs/ConstitutionRAG).

- **React Native Interface**  
  A user-friendly React Native interface for mobile access is available on GitHub: [RAG Project Interface](https://github.com/dinushasandamali/Rag_Project).

## Requirements

- Python 3.x
- Jupyter Notebook
- Hugging Face Transformers
- PyTorch
- Tensorflow
- FAISS for efficient indexing