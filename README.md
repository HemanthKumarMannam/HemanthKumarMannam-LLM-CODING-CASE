Kuwait IMF Report Analysis

This project uses Python and Google Gemini to analyse Kuwait’s 2025 Article IV consultation report, published in February 2026.

Features

PDF text extraction, cleaning and OCR fallback.

Section summaries of fewer than 100 words.

Seven-theme keyword analysis and economic strengths and vulnerabilities.

Structured numerical extraction with source evidence and missing-value handling.

MiniLM embeddings and FAISS retrieval.

Single-query and multi-query RAG comparison.

Automated judge evaluation and a four-panel financial dashboard.

Local caching of extracted text, embeddings and API responses.

How to Run

Open the notebook in Google Colab.

Download the IMF source PDF.

Rename it to kuwait_2026_imf_data.pdf and upload it to Colab’s /content folder.

Create a Gemini API key through Google AI Studio.

Add the key to Colab Secrets as AI_KEY and enable notebook access.

Run all notebook cells in order, including the extension and dashboard cells.

The notebook installs its required packages. API access and sufficient quota are required. Do not include your API key in the notebook or repository.
