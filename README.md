## 🎥 IMDB Review Sentiment Analysis with Streamlit 🚀

A simple Streamlit app for IMDB movie review sentiment analysis using a pre-trained RNN model (simple_rnn_imdb.h5) with TensorFlow/Keras.

## 🚀 How to Run
```bash
# Clone the repository
git clone https://github.com/eensaydn/Deep-Learning-Project.git
cd your-repo-name

## Install dependencies
pip install -r requirements.txt

## Run the app
streamlit run app.py

##⚡ How It Works
Enter any movie review text in the text area.

The app will classify it as Positive or Negative based on the RNN model.

## 📌 Example
Input: "This movie is so good"

Output: "Sentiment: Positive | Prediction Score: 0.95"

## 📁 File Structure
├── README.md
├── requirements.txt
├── app.py                # Streamlit app
└── simple_rnn_imdb.h5    # Pre-trained model
