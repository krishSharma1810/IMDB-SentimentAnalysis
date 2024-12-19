
# IMDB Sentiment Analysis

This project performs sentiment analysis on IMDB movie reviews, classifying them as positive or negative using various machine learning models.

## Features

- Data preprocessing and embedding visualization.
- Implementation of Recurrent Neural Network (RNN) models.
- Prediction on new data inputs.

## Prerequisites

- Python 3.11.11 or higher.
- Required Python packages listed in `requirements.txt`.

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/krishSharma1810/IMDB-SentimentAnalysis.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd IMDB-SentimentAnalysis
   ```
3. **Install the dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Data Preprocessing and Embedding Visualization:**
   - Use `embedding.ipynb` to preprocess data and visualize embeddings.

2. **Model Training:**
   - Execute `IMDB_project.ipynb` to train the RNN model on the dataset.

3. **Prediction:**
   - Utilize `prediction.ipynb` to make sentiment predictions on new movie reviews.

4. **Main Script Execution:**
   - Run `main.py` using Streamlit for end-to-end execution:
     ```bash
     streamlit run main.py
     ```

## Project Structure

- `IMDB_project.ipynb`: Notebook for data preprocessing and model training.
- `embedding.ipynb`: Notebook for embedding visualization.
- `prediction.ipynb`: Notebook for making predictions on new data.
- `main.py`: Main script to execute the complete workflow.
- `requirements.txt`: Contains the list of dependencies.
- `simple_rnn_imdb.h5`: Pre-trained RNN model file.

## Dataset

The IMDB dataset used in this project contains 50,000 movie reviews labeled as positive or negative. It can be downloaded from [Kaggle](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews).

## Contributions

Contributions are welcome! Feel free to fork the repository, make enhancements, and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any queries, reach out to [Krish Sharma](mailto:sharmakrish1810work@gmail.com).
