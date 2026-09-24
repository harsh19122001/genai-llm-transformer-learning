# GenAI, LLM & Transformer Learning 🚀

This repository contains my hands-on learning and practice while learning
NLP, Large Language Models and Transformer-based models.

I am focusing more on understanding the concepts, flow and working of the
models instead of memorizing every line of code.

## Topics Covered

### NLP Basics
- Tokenization
- Bag of Words
- TF-IDF
- Word2Vec

### Embeddings
- Sentence Embeddings
- Cosine Similarity
- Semantic Search
- Vector Search with FAISS

### Transformer
- Attention
- Query, Key and Value (Q, K, V)
- Scaled Dot-Product Attention
- Causal / Masked Attention
- Positional Encoding
- Multi-Head Attention
- Feed Forward Network
- Residual Connection
- Layer Normalization

### BERT, GPT & T5
- BERT
- GPT-style Text Generation
- T5
- Encoder-only Transformer
- Decoder-only Transformer
- Encoder-Decoder Transformer

### LLM Generation
- Next Token Prediction
- Logits
- Softmax
- Temperature
- Top-k Sampling
- Top-p Sampling
- Hugging Face Model Generation

## Notebook Structure


genai-llm-transformer-learning/
│
├── README.md
│
├── 01_NLP_Basics/
│   ├── 01_tokenization.ipynb
│   ├── 02_bag_of_words.ipynb
│   ├── 03_tfidf.ipynb
│   └── 04_word2vec.ipynb
│
├── 02_Embeddings/
│   ├── 01_sentence_embeddings.ipynb
│   ├── 02_cosine_similarity.ipynb
│   └── 03_semantic_search.ipynb
│
├── 03_Transformer/
│   ├── 01_attention.ipynb
│   ├── 02_qkv_attention.ipynb
│   ├── 03_causal_masking.ipynb
│   ├── 04_positional_encoding.ipynb
│   ├── 05_multi_head_attention.ipynb
│   ├── 06_feed_forward_network.ipynb
│   └── 07_residual_layernorm.ipynb
│
├── 04_LLM_Transformer/
│   └── bert_gpt_t5_llm_generation.ipynb
│
└── requirements.txt


NLP
 ↓
Tokenization
 ↓
Text Representation
 ↓
Embeddings
 ↓
Transformer
 ↓
Attention
 ↓
BERT / GPT / T5
 ↓
LLM Generation


Libraries Used
Python
Jupyter Notebook
NumPy
Pandas
Matplotlib
Scikit-learn
Gensim
Sentence Transformers
FAISS
Hugging Face Transformers
PyTorch

What I Learned

The main idea I understood from this learning is:

Tokenizer → breaks text into tokens

Embedding → represents meaning as numbers

Attention → finds important relationships

Transformer → processes relationships between tokens

LLM → predicts the next token and generates text
