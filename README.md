## Introduction
This project focuses on analyzing the sentiment of user reviews for the Gojek application. It utilizes a Long Short-Term Memory (LSTM) deep learning model to classify reviews as positive, negative, or neutral. The dataset comprises 30,000 reviews scraped directly from the Google Play Store.

## Data Scraping
The user reviews were collected from the Google Play Store using the script provided in the `Scrapping_Data.ipynb` Jupyter Notebook. This notebook contains the necessary code to perform the web scraping tasks. The collected data, comprising 30,000 reviews, is then compressed into `gojek-app_review.zip`.

## Sentiment Analysis
The core of this project is the sentiment analysis performed by the `Analisis_Sentimen.ipynb` Jupyter Notebook. This notebook implements a Long Short-Term Memory (LSTM) neural network to classify the sentiment of the scraped Gojek app reviews. The model processes the review text and categorizes each review as positive, negative, or neutral. This involves steps such as data preprocessing (cleaning text, tokenization), model training, and evaluation of the model's performance.

## Setup and Usage

### Prerequisites
- Python 3.x
- Jupyter Notebook or JupyterLab

### Dependencies
All required Python libraries are listed in the `requirements.txt` file. Install them using pip:
```bash
pip install -r requirements.txt
```

### Running the Project
1.  **Data Scraping:**
    Open and run the `Scrapping_Data.ipynb` notebook in a Jupyter environment. This will scrape the Gojek app reviews from the Google Play Store and save them (e.g., as `gojek-app_review.zip`).
2.  **Sentiment Analysis:**
    Once the data is collected, open and run the `Analisis_Sentimen.ipynb` notebook. This notebook will load the scraped data, preprocess it, train the LSTM model, and perform sentiment classification.

## Project Structure
- `Analisis_Sentimen.ipynb`: Jupyter Notebook for sentiment analysis using LSTM.
- `Scrapping_Data.ipynb`: Jupyter Notebook for scraping Gojek app reviews.
- `gojek-app_review.zip`: Compressed file containing the scraped review data.
- `requirements.txt`: Lists the Python dependencies for this project.
- `LICENSE`: Contains the license information for the project.
- `README.md`: This file, providing an overview of the project.

## License
This project is licensed under the terms of the [MIT License](LICENSE).
