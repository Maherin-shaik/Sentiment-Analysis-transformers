# 💬 Sentiment Analysis with Transformers
**Live Demo**
https://sentiment-analysis-transformers-ldf9dss4zxqqdj5xvust9m.streamlit.app/

This project is a **Sentiment Analysis web application** built during my Data Science training to understand and apply **Natural Language Processing (NLP) using Transformer-based models**.
The application analyzes user-provided text and predicts whether the sentiment is Positive or Negative, along with confidence scores.

The app is developed using Streamlit for the frontend and Hugging Face Transformers for state-of-the-art NLP modeling.

### 🚀 Features

- 🔍 Analyze sentiment of any English text
- 🤖 Uses a pre-trained transformer model (siebert/sentiment-roberta-large-english)
- 📊 Displays confidence scores for each sentiment
- 😊 Emoji-based sentiment visualization
- ⚡ Fast inference with cached model loading
- 🖥️ Interactive and user-friendly Streamlit UI
- 🧠 Model Used
- Model Name: siebert/sentiment-roberta-large-english
- Architecture: RoBERTa
- Task: Sentiment Analysis
- Output Labels: POSITIVE, NEGATIVE

This model is fine-tuned on multiple sentiment datasets and provides high accuracy for real-world text.

### 🛠️ Tech Stack
- Python
- Streamlit
- Hugging Face Transformers
- Pandas
- PyTorch

### 📂 Project Structure
sentiment-analysis-app/<br>
│<br>
├── app.py<br>
├── sentiment_utils.py<br>
├── requirements.txt<br>
├── README.md<br>
├── .gitignore<br>
└── sentiment_env/<br>

### ▶️ How to Run Locally
1️⃣ Clone the Repository
```
git clone https://github.com/your-username/sentiment-analysis-with-transformers.git
cd sentiment-analysis-with-transformers
```
2️⃣ Create Virtual Environment
```
python -m venv sentiment_env
```

Activate it:
```
Windows
sentiment_env\Scripts\activate

Linux / Mac
source sentiment_env/bin/activate
```

3️⃣ Install Dependencies
```
pip install -r requirements.txt
```
4️⃣ Run the Streamlit App
```
streamlit run app.py
```
### 📊 Example Output

**Predicted Sentiment**: 😊 POSITIVE<br>
**Confidence Score**: 98.45%<br>
**Detailed Table:** Shows confidence for all labels

### 🎓 Learning Outcome

- Through this project, I gained hands-on experience in:
- Using transformer models for NLP tasks
- Integrating ML models with Streamlit
- Model caching and optimization
- Building end-to-end data science applications

This project was completed as part of my Data Science training, focusing on applying theory to real-world applications.

### 👤 Author

**Shaik Maherrin**<br>
Computer Science Student<br>
Data Science & Full Stack Development

### ⭐ Acknowledgements

- Hugging Face 🤗
- Streamlit
- Open-source NLP community
