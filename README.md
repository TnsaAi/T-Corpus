# TCorpus

## Overview
TCorpus is a comprehensive dataset containing 1 million lines of books data curated and extracted by TNSA Web Scrapers. Designed for AI and ML researchers, TCorpus provides an extensive resource for building and fine-tuning Natural Language Processing (NLP) models, including language models, chatbots, summarization systems, and more.

## Features
- **Extensive Dataset**: Contains 1M lines of high-quality books data from various genres and authors.
- **Versatile Applications**: Ideal for NLP tasks such as language modeling, sentiment analysis, summarization, translation, and more.
- **Cleaned and Preprocessed**: The dataset has been cleaned for optimal usability, ensuring minimal noise for training purposes.
- **TNSA Web Scrapers**: Data is extracted using proprietary TNSA scraping tools, ensuring quality and accuracy.

## Repository Structure
```
.
├── data/
│   ├── train_data.txt      # Training data
│   ├── val_data.txt        # Validation data
│   └── test_data.txt       # Test data
├── scripts/
│   ├── preprocess.py       # Script for additional preprocessing
│   └── data_stats.py       # Script for analyzing the dataset
├── README.md               # Project overview and details
└── LICENSE                 # License for the repository
```

## Usage
Clone the repository:
```bash
git clone https://github.com/TnsaAi/T-Corpus.git
cd T-Corpus
```

Explore the data:
- **Training Data**: `data/train_data.txt`
- **Validation Data**: `data/val_data.txt`
- **Test Data**: `data/test_data.txt`

Analyze the data using provided scripts:
```bash
python scripts/data_stats.py
```

## Data Details
- **Size**: 1M lines of text
- **Sources**: Books from multiple genres and authors (public domain and licensed sources).
- **Format**: Plain text file with one line of text per entry.
- **Languages**: Primarily English.

## How to Contribute
We welcome contributions to improve the dataset or scripts! To contribute:
1. Fork the repository.
2. Make your changes in a new branch.
3. Submit a pull request with a detailed explanation.

## License
This repository is licensed under the MIT License. See the LICENSE file for more details.

## Acknowledgments
TCorpus is powered by TNSA Web Scrapers, leveraging advanced scraping and data curation techniques.

For inquiries or collaboration opportunities, contact the TNSA AI team.
