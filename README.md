# Automated Processing and Sentiment Tagging of News Data

A Python-based tool for automated quality control, metadata extraction, and sentiment tagging of multilingual news data in Excel format. Utilizes Pandas, NumPy, Openpyxl, and Ollama (Mistral model) for advanced NLU and financial sentiment analysis.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Example Data Columns](#example-data-columns)
- [Potential Extensions](#potential-extensions)
- [License](#license)

---

## Overview

This project automates quality control, metadata extraction, and sentiment tagging for large-scale, multilingual news and social media datasets provided in Excel format. It leverages Python (Pandas, NumPy, Openpyxl) for robust data processing and integrates the open-source Ollama platform (Mistral model) for advanced natural language understanding (NLU) and sentiment analysis. Data is manually downloaded and then processed with this tool, supporting financial and market news analysis.

---

## Features

- Automated preprocessing and analysis of Excel datasets (50+ columns)
- Multilingual data handling (Hindi, Malayalam, Telugu, English, etc.)
- Metadata extraction: headlines, sources, influencers, sentiment tags, document IDs, and more
- Advanced NLU and sentiment tagging via Ollama (Mistral model)
- Designed for financial and market news

---

## Technologies Used

- Python 3.13+
- Pandas
- NumPy
- Openpyxl
- Ollama (Mistral model)

---

## Getting Started

### Installation

```bash
pip install pandas openpyxl
# Download and set up Ollama and the Mistral model
ollama run mistral:latest
```

### Data Preparation

- Manually download your Excel data file and place it in your working directory.

---

## Usage

1. **Load the Excel file:**
   ```python
   import pandas as pd
   data = pd.read_excel('your_data_file.xlsx')
   ```
2. **Process and analyze the data using the provided scripts or notebook.**
3. **Use the Ollama API with the Mistral model for NLU and sentiment tagging tasks.**

---

## Example Data Columns

- Date
- Headline
- URL
- Opening Text
- Hit Sentence
- Combined Sentence
- Source
- Influencer
- Country
- Subregion
- Language
- Sentiment
- Shares
- Reactions
- Threads
- Is Verified
- Body
- Parent URL
- Document Tags
- Document ID
- Custom Categories
- ...and more (over 50 columns)

---

## Potential Extensions

- Dashboard development for QC and sentiment visualization
- Integration with additional NLU or analytics models
- Expansion to other industries or data types

---

## License

MIT License

---
