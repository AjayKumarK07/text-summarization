
# Text Summarization Model

This repository demonstrates a machine learning-based text summarization model. The project focuses on generating concise and meaningful summaries from text data using advanced natural language processing (NLP) techniques. This implementation is designed for both extractive and abstractive summarization tasks, leveraging state-of-the-art methodologies.

## Features

- Preprocessing of text data, including tokenization and stopword removal.
- Implementation of Transformer-based models (e.g., BERT, GPT, T5) for text summarization.
- Evaluation using ROUGE and BLEU metrics.
- Comparative analysis with existing models.
- Customizable for domain-specific summarization tasks.

## Dataset

The dataset used for this project contains news articles with their corresponding headlines. Below is a sample of the dataset:

| Headlines                                           | Text                                                                                  |
|----------------------------------------------------|--------------------------------------------------------------------------------------|
| upGrad learner switches to career in ML & AI       | Saurav Kant, an alumnus of upGrad and IIIT-B's ...                                    |
| Delhi techie wins free food from Swiggy for one year | Kunal Shah's credit card bill payment platform ...                                   |
| New Zealand end Rohit Sharma-led India's streak     | New Zealand defeated India by 8 wickets in the ...                                   |

## Methodology

### Feature Engineering

The text is preprocessed through:
- Tokenization
- Stopword removal
- Named entity recognition (NER)
- Use of pre-trained embeddings like Word2Vec and GloVe

### Model Training

Transformer-based models like BERT, GPT, and T5 are fine-tuned for summarization tasks. Training involves adjusting model weights using backpropagation and optimizing for text similarity and coherence.

### Model Evaluation

- **Automatic Metrics**: ROUGE and BLEU scores are used to evaluate the summaries against reference summaries.

## Results

- Achieved high ROUGE and BLEU scores, demonstrating the model's capability to generate accurate and concise summaries.
- Compared performance with existing models like BERTSUM and GPT-3, showing competitive results.

## Future Work

- Improve model accuracy by incorporating user feedback and expanding the training dataset.
- Develop real-time summarization capabilities for live data streams.
- Enhance cross-domain summarization to handle diverse text types and sentiments.

## Limitations

- Dependency on high-quality, diverse training data.
- Difficulty in summarizing ambiguous or highly technical content.
- Computational requirements for training large Transformer-based models.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AjayKumarK07/text-summarization.git
   ```

2.  Download the glove from the following link 
	https://www.kaggle.com/datasets/yutanakamura/glove42b300dtxt
