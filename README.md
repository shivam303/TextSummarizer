# End-to-End NLP Text Summarization Project

This project is an end-to-end NLP project that summarizes text using models from the Hugging Face library. The entire pipeline is designed to be modular and scalable, following MLOps best practices.

## Workflow

1.  **Configuration Setup**: Initialize configurations from `params.yaml` and `config/config.yaml`.
2.  **Data Ingestion**: Fetch and load the dataset.
3.  **Data Validation**: Validate the integrity and format of the data.
4.  **Data Transformation**: Preprocess and tokenize the text data.
5.  **Model Training**: Fine-tune a pre-trained model from Hugging Face on the custom dataset.
6.  **Model Evaluation**: Evaluate the trained model on a test set.
7.  **Prediction Pipeline**: Use the trained model to summarize new text.

## Getting Started

### Prerequisites

- Python 3.8 or later
- pip
- virtualenv (recommended)

### Installation

1.  **Clone the repository:**

    ```bash
    git clone https://github.com/your-username/TextSummarizer.git
    cd TextSummarizer
    ```

2.  **Create a virtual environment:**

    ```bash
    python -m venv .venv
    source .venv/bin/activate  # On Windows, use `.venv\Scripts\activate`
    ```

3.  **Install the dependencies:**

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the training pipeline:

```bash
python main.py
```

To use the summarization service (once the `app.py` is implemented):

```bash
python app.py
```
