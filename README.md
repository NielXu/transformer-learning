# Transformer Learning
This project is designed for educational purposes, providing a hands-on approach to understanding and experimenting with transformer models. It aims to help learners grasp the fundamental concepts and practical applications of this powerful architecture.

# Learning Process
- Notebooks 01 to 09 is all the fundmental concepts about transformer:
    - Explain the basic of tokenization and embedding
    - Explain what is positional encoding and why is it needed
    - Explain what is attention, the most important part in the transformer architecture
    - Explain what is add & norm and why do we need it
    - Implement a simple encoder, decoder, and encoder-decoder combined transformer
    - Train a tokenizer and an encoder-decoder combined transformer
- Notebooks 10 - 12 are done and written in [Google Colab](https://colab.google/), because it provides GPU usage to speed up the training process. Also recommended the import and run them on Google Colab:
    - Train an encoder-decoder combined transformer for the translation task (EN to ZH)
    - Train a decoder-only transformer for text completion (EN)
    - Fine tuning a BERT model for sequence classification (Yelp review to stars)

# Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries (install via `requirements.txt` if provided)

# Data
- [en-zh.txt](./data/en-zh.txt/): this data is from http://opus.nlpl.eu, check out the folder README for more info
- [tiny_shakespeare.txt:](./data/tiny_shakespeare.txt): downloaded online

# Acknowledgments
Inspired by the original transformer paper: ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762).

# Disclaimer
This code is provided for learning purposes only. It is not production-ready and may not be optimized for efficiency. There might be mistakes in the implementation. Feel free to open an issue to report any errors or provide feedback.
