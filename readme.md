
# Text Preprocessing and Classification Pipeline (SATRIA DATA 2024)

## Overview  
This is an end-to-end text preprocessing and classification pipeline designed to process and categorize text data efficiently. It includes a comprehensive preprocessing module to clean, normalize, and tokenize text before feeding it into a deep learning model for classification.  

## Features  
### Text Preprocessing  
- **Text Cleaning**: Removing duplicates, punctuation, numbers, URLs, and special characters.  
- **Tokenization**: Splitting text into tokens using NLP libraries.  
- **Stopword Removal**: Filtering out common words to enhance text quality.  
- **Stemming & Lemmatization**: Reducing words to their base form for better consistency.  
- **Slang Normalization**: Converting informal words into formal equivalents.  
- **KBBI Filtering**: Ensuring words exist in the official Indonesian dictionary (KBBI).  
- **Translation**: Converting English words into Indonesian if necessary.  
- **Unique Word Extraction**: Optional feature to extract distinct words for analysis.  

### Deep Learning Classification  
- **Transformer-based Model**: Uses IndoBERTweet for classification.  
- **Custom Dataset Handling**: Allows training with labeled datasets.  
- **Balanced Accuracy Metric**: Evaluates classification performance.  
- **Batch Prediction**: Efficient processing of large datasets.  

## Installation  
Ensure you have Python installed, then install the required dependencies:  
```bash
pip install numpy pandas scikit-learn nltk matplotlib Sastrawi preprocessor torch transformers deep-translator
```
Download necessary NLTK datasets:  
```python
import nltk
nltk.download('wordnet')
nltk.download('stopwords')
nltk.download('punkt')
```

## Usage  
### 1. Clone the Repository  
```bash
git clone https://github.com/yourusername/clean-flow.git
cd clean-flow
```


## Contributing  
We welcome contributions! Please open an issue or submit a pull request to help improve this project.  

## License  
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.  
