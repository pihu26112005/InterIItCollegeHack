# Project Name: Google Lens Pro Max and Hog Ragger

## How to Run the Repo for Inference

This repo contains two `.ipynb` notebooks that are designed to run on Google Colab with T4 GPU support. Below are the steps to run each notebook:

### 1. **Google Lens Pro Max**

- Open the `Google Lens Pro Max.ipynb` file in Google Colab.
- Make sure you're using the T4 GPU in Colab.
- If you encounter any errors, restarting the Colab session usually resolves them.
- Ensure you have access to the gated Hugging Face models (mentioned in the `requirements.txt`).
- Simply run the entire notebook and provide an image and user input when prompted.
- After running all cells, you’ll receive a list of website metadata related to the image and input query.

### 2. **Hog Ragger**

- Open the `Hog Ragger.ipynb` file in Google Colab, also using the T4 GPU.
- You will need the `embeddings` and `corpus.json` files that are included in the repo.
- As with the previous notebook, make sure you have access to the necessary gated Hugging Face models.
- Run the file, providing user input when prompted. Note that generating the output may take some time.

### Important Note:
- Both notebooks require access to specific Hugging Face gated repositories, which are listed in the `requirements.txt` file. Ensure you have a Hugging Face account and the necessary permissions before running the notebooks.

---

## Folder Structure
There is no specific folder structure in this repo. All files are located at the root level.

---

## Tech Stack

### **Google Lens Pro Max**
- Google Colab (with T4 GPU)
- Hugging Face Open Source LLM Model (LLama-3.1)
- Transformers
- Open Source Image Processing Models (BLIP)
- SERP API

### **Hog Ragger**
- Google Colab (with T4 GPU)
- Hugging Face Open Source LLM Models (LLama-3)
- Transformers
- Retrieval-Augmented Generation (RAG)
- ChromaDB

---

## Requirements

To run the notebooks, you need:
- A Hugging Face account with access tokens and permissions for the following gated repositories:
  - `meta-llama/Llama-3.1-8B-Instruct`

Make sure all dependencies are fulfilled before running the notebooks.
