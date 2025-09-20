# IMDB Movie Review Sentiment Analysis with Simple RNN

This project demonstrates sentiment classification of IMDB movie reviews using a Simple RNN model built with TensorFlow/Keras. It includes a Streamlit web app for interactive prediction, allowing users to input reviews and receive real-time sentiment analysis.

## Features

- Loads and preprocesses IMDB reviews using Keras's word index.
- Trains a Simple RNN model for binary sentiment classification (positive/negative).
- Saves and loads the trained model (`imdb_sentiment_model.h5`).
- Interactive web interface built with Streamlit for user input and prediction.
- Displays sentiment prediction and confidence score.

## Files

- `imdb_text_classification.ipynb`: Jupyter notebook for data loading, preprocessing, model training, and saving.
- `app.py`: Streamlit web application for sentiment analysis.
- `imdb_sentiment_model.h5`: Pre-trained Keras model (required for predictions).
- `requirements.txt`: List of required Python packages.

## Usage

1. **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

2. **Train the model (optional):**
   - Run `imdb_text_classification.ipynb` to train and save the model as `imdb_sentiment_model.h5`.

3. **Run the Streamlit app:**
    ```bash
    streamlit run app.py
    ```

4. **Interact:**
   - Enter a movie review in the text area.
   - Click "Classify" to see the predicted sentiment and score.

## Notes

- Ensure `imdb_sentiment_model.h5` is present in the project directory for the app to work.
- The app uses the IMDB dataset's word index for preprocessing user input.

---

**Author:** Lakshay Sindhu  