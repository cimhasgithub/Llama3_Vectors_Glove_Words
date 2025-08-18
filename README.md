# LLaMA3-8B Embedding Vectors with GloVe Vocabulary  

This repository contains **precomputed LLaMA embedding vectors** generated using the **GloVe vocabulary** (~350k+ words). These embeddings are taken from the **last layer (32)** of the LLaMA 3-8B model.  

## Overview  
- **Vocabulary:** GloVe vocabulary with over 350,000 words  
- **Embedding size:** Original vectors are size **4096** (from the last layer (32))  
- **Dimensionality Reduction:** Applied PCA (Principal Component Analysis) to produce smaller-dimensional embeddings  
- **Available files:** Text files containing the  words and its corresponding embeddings  
- **Direct link:** Download link for the full-size (4096-dimension) embeddings provided below  

## Contents (File Information)  

| File Name                         | Dimensions | Approx. Size (MB) |
|-----------------------------------|------------|-------------------|
| `llama_pca_1_layer_32.txt`        | 1       | 6              | 
| `llama_pca_2_layer_32.txt`        | 2       | 9              | 
| `llama_pca_4_layer_32.txt`        | 4       | 16               | 
| `llama_pca_8_layer_32.txt`        | 8        | 28               | 
| `llama_pca_16_layer_32.txt`       | 16        | 54                | 
| `llama_pca_32_layer_32.txt`       | 32        | 105                | 
| `llama_pca_50_layer_32.txt`       | 50         | 162                |
| `llama_pca_64_layer_32.txt`       | 64         | 206                |
| `llama_pca_128_layer_32.txt`      | 128         | 410                | 
| `llama_pca_256_layer_32.txt`      | 256         | 817                 | 
| `llama_pca_512_layer_32.txt`      | 512          | 1590                | 



> **Note:** Sizes are approximate and may vary slightly depending on compression.  

## How these vectors are created
<img width="656" height="353" alt="image" src="https://github.com/user-attachments/assets/421a3c0d-b189-456a-8843-2f0afd1b04ca" />


## Usage  
You can use these embedding vectors for a variety of NLP tasks, including:  
- Semantic search  
- Text similarity  
- Transfer learning  
- Downstream language tasks  

Simply load the vectors into your environment and map words to their corresponding embeddings based on the GloVe vocabulary.  
