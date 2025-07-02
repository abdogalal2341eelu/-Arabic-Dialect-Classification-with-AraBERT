## Overview
This project performs multi-class classification on Arabic text to detect **26 different Arabic dialects** using a fine-tuned **AraBERT** model. It includes a pre-trained model and tokenizer ready for deployment or inference.

## Features
- Preprocessing with custom WordPiece tokenizer
- Fine-tuned AraBERT transformer model
- Supports 26 dialect classes (e.g. EGY, GLF, MSA, LAV, etc.)
- Google Colab notebook for easy training/testing
- Ready for inference using HuggingFace Transformers

## Technologies
- Python
- PyTorch
- HuggingFace Transformers
- AraBERT
- Google Colab

## Files
- `model/model.pt`: Fine-tuned AraBERT model weights
- `tokenizer/tokenizer.json`: Tokenizer configuration
- `tokenizer/tokenizer_config.json`: Tokenizer settings
- `tokenizer/vocab.txt`: WordPiece vocabulary
- `notebooks/dialect_classification.ipynb`: Google Colab training notebook
- `requirements.txt`: Project dependencies

## How to Run

1. Install dependencies:
```bash
pip install -r requirements.txt
