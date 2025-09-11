# Text_Summarizer

# Project Description

This project is a PDF Text Summarizer built using Python, PyTorch, and Hugging Face Transformers. The system enables users to upload PDF documents, automatically extract text, and generate concise summaries.

# The pipeline works as follows:

PDF Handling – Text is extracted from uploaded PDFs using PyPDF2.

Preprocessing – The extracted content is cleaned and prepared for the model.

Summarization Model – A pretrained T5-Small model (T5Tokenizer, T5ForConditionalGeneration) is used for abstractive summarization. Summaries are generated with beam search decoding to improve quality.

Platform & Optimization – Implemented in Google Colab, leveraging PyTorch with GPU acceleration when available for faster inference.

# Outcome

The project delivers an end-to-end text summarization pipeline that transforms lengthy PDF documents into clear, concise, and human-readable summaries. It highlights the effectiveness of transformer-based NLP models in real-world document understanding and knowledge distillation.
