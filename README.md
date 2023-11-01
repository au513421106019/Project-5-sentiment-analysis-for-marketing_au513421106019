Dataset Link: https://www.kaggle.com/datasets/crowdflower/twitter-airline-sentiment

# Sentiment Analysis for Marketing

This README provides instructions on how to run the code for sentiment analysis in marketing. The code helps analyze customer sentiment towards your marketing campaigns or products using Natural Language Processing (NLP) techniques. It utilizes Python and several libraries for text processing and sentiment classification.

#  Table of Contents

1. [Dependencies](#dependencies)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Configuration](#configuration)
5. [Output](#output)

## Dependencies

Make sure you have the following dependencies installed:

- Python (3.6+)
- pip (Python package manager)
- Virtual environment (optional but recommended)
- The following Python libraries:
  - `nltk` for natural language processing
  - `pandas` for data manipulation
  - `scikit-learn` for machine learning
  - `textblob` for sentiment analysis
  - `matplotlib` for visualizations

You can install the required Python libraries using the provided `requirements.txt` file.

## Installation

1. Clone the repository:

   `git clone https://github.com/au513421106019/Project-5-sentiment-analysis-for-marketing_au513421106019.git
   ```

2. (Optional) Create and activate a virtual environment:

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Prepare your data:
   - Ensure your marketing text data is in a suitable format, such as a CSV file with a column containing the text data you want to analyze. You may also include a column for labels if you have pre-labeled data (e.g., positive, negative, neutral).

2. Update the configuration (see next section).

3. Run the sentiment analysis script:

   ```bash
   python sentiment_analysis.py
   ```

4. The script will perform sentiment analysis on your data, and you will see the results printed in the terminal or saved to an output file (configurable).

## Configuration

Before running the code, you need to configure the `config.json` file to suit your needs. Here are the parameters you can configure:

- `data_file`: Path to the input data file (e.g., "data.csv").
- `text_column`: The name of the column containing the text data.
- `label_column` (optional): The name of the column containing labels (if available).
- `output_file`: Path to the output file where sentiment analysis results will be saved.
- `output_format`: Choose between "csv" or "json" for the output file format.
- `visualize`: Set to `true` if you want to generate sentiment distribution visualizations.
- `stopwords_removal`: Set to `true` to enable stopwords removal during text preprocessing.

## Output

The script will generate sentiment analysis results, including the sentiment polarity and subjectivity of each piece of text. If you provide labels in your data, it will also include accuracy metrics. Visualizations (if enabled) will be saved in the output directory.

Feel free to reach out if you have any questions or encounter issues. Happy sentiment analysis for marketing!# Project-5-sentiment-analysis-for-marketing_au513421106019
