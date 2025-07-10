# Multimodal Review Classification & Summarization using Transformers and CNN

This project leverages **transformers** and **convolutional neural networks (CNNs)** to analyze and classify Amazon customer reviews, using both text and image data. It also includes a **fine-tuned BART-based LLM** to generate concise summaries for business reporting, helping enhance customer feedback analysis and operational decision-making.

## 🚀 Project Overview

- **Goal**: Automatically classify Amazon reviews into four major issue categories and summarize them for managerial insight.
- **Approach**:
  - Applied a **transformer-based NLP pipeline** for text classification.
  - Fine-tuned a **BART model** to generate management-level summaries.
  - Built a **CNN model** to process review images.
  - Combined text and image features using **early fusion**, improving classification accuracy by **14%** compared to late fusion.