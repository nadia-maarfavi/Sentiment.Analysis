# Sentence Sentiment Analysis
This repository contains three different approaches for performing sentiment analysis on sentences. Each approach utilizes a different model or service:
**1. BERT (BertKtrain.ipynb)**
**2. Google Cloud NLP API (GoogleCloudAPI.ipynb)**
**3. XLNet (XLNet_Transformers.ipynb)**

## Introduction
Sentiment analysis is the process of determining whether a piece of text is positive, negative, or neutral. This repository demonstrates three methods to perform sentiment analysis using different machine learning models and services.

## Models
### BERT
**File: BertKtrain.ipynb**

BERT (Bidirectional Encoder Representations from Transformers) is a transformer-based model developed by Google. It is designed to understand the context of a word in search queries. In this notebook, we utilize the ktrain library, which provides a simple interface for training and deploying BERT models for sentiment analysis.

### Google Cloud NLP API
**File: GoogleCloudAPI.ipynb**

Google Cloud Natural Language API is a cloud-based service that uses machine learning to reveal the structure and meaning of text. The API can perform sentiment analysis, entity recognition, and syntax analysis. This notebook demonstrates how to use the Google Cloud NLP API to analyze the sentiment of sentences.

### XLNet
**File: XLNet_Transformers.ipynb**

XLNet is a generalized autoregressive pretraining method that leverages the best of both autoregressive and autoencoding models, like BERT. It is designed to overcome limitations in BERT by capturing bidirectional context. This notebook uses the transformers library by Hugging Face to implement sentiment analysis using the XLNet model.

## Setup and Installation
To run these notebooks, you need to install the required packages and set up any necessary credentials.

**1. Clone the repository:**

```bash
git clone https://github.com/yourusername/sentence-sentiment-analysis.git
cd sentence-sentiment-analysis
```

**2. Install dependencies:**

**- Create a virtual environment (optional but recommended):**
```bash
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`
```

**- Install the required packages:**

```bash
pip install -r requirements.txt
```

**3. Google Cloud NLP API:**

- Set up a Google Cloud project and enable the Natural Language API.
- Download the service account key and set the GOOGLE_APPLICATION_CREDENTIALS environment variable:
```bash
export GOOGLE_APPLICATION_CREDENTIALS="path/to/your/service-account-file.json"
```

## Usage
Each notebook is self-contained and includes instructions for loading data, preprocessing, and running sentiment analysis.

BertKtrain.ipynb: Open the notebook and follow the steps to train and evaluate the BERT model using ktrain.
GoogleCloudAPI.ipynb: Follow the instructions to use the Google Cloud NLP API for sentiment analysis.
XLNet_Transformers.ipynb: Use the notebook to implement and run sentiment analysis with the XLNet model using Hugging Face's transformers library.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
