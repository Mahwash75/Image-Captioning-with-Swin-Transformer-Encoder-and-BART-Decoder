
## 📌 Title

**Image Captioning with Swin Transformer Encoder and BART Decoder**

## 🔹 Description

This project implements an **image captioning model** by combining a **Swin Transformer (Tiny)** as the visual encoder with **BART (Base)** as the text decoder using Hugging Face’s `VisionEncoderDecoderModel`. The model is trained and evaluated on the **Kag100 image captioning dataset**.

The pipeline includes:

* **Feature Extraction**: Images are processed with the Swin Transformer feature extractor.
* **Text Tokenization**: Captions are tokenized with BART’s tokenizer.
* **Model Training**: The Swin-BART model is fine-tuned using Hugging Face’s `Trainer` API with custom preprocessing and evaluation.
* **Evaluation**: Performance is measured using **Word Error Rate (WER)**.
* **Visualization**: Sample images with their captions are plotted for quick inspection.

## 🔹 Key Features

* End-to-end **image → text generation** pipeline.
* Integration of **Vision Transformer (Swin)** and **Sequence-to-Sequence Transformer (BART)**.
* Custom preprocessing pipeline with Hugging Face `datasets`.
* Training with configurable hyperparameters and checkpoint saving.
* Evaluation with **WER metric** to assess caption quality.

## 🔹 Tech Stack

* Python, PyTorch, NumPy, Matplotlib
* Hugging Face Transformers & Datasets
* OpenCV (for preprocessing if needed)
* NLTK (sentence tokenization for evaluation)

## 🔹 Outcome

The project successfully generates natural language captions for images by leveraging the **power of vision-language models**. It demonstrates how transformer-based encoders and decoders can be combined for multimodal tasks such as image captioning.

---

👉 Do you want me to also create a **short one-paragraph version** (for the repo tagline) like we did for the other projects?
