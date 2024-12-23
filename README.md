### README for Twitter Sentiment Analysis Project

---

#### Project Overview
This project is a **Twitter Sentiment Analysis** tool built using **Django**. The tool allows users to manually input a tweet, which is then analyzed to determine whether the sentiment is **positive** or **negative**. 

The model has been trained on the **Sentiment140 dataset**, consisting of **1.6 million tweets**, to classify tweets based on their sentiment.

---

#### Features
- **Sentiment Analysis**: Classifies tweets as **positive** or **negative**.
- **Web Interface**: A simple and interactive web page for users to input tweets.
- **Emoji Feedback**: Displays a **smiling emoji 😊** for positive tweets and a **sad emoji 😢** for negative tweets.
- **Efficient Model**: Trained on a large dataset for reliable sentiment classification.

---

#### Dataset
- **Name**: Sentiment140 Dataset
- **Size**: 1.6 million labeled tweets
- **Labels**: 
  - `0`: Negative Sentiment
  - `4`: Positive Sentiment
- **Source**: The dataset captures real-world tweets, making the model robust for sentiment detection in casual language.

---


---

#### Installation Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-repo/twitter-sentiment-analysis.git
   cd twitter-sentiment-analysis
   ```

2. **Set up a Python Environment**:
   ```bash
   python -m venv venv
   source venv/bin/activate   # On Windows, use venv\Scripts\activate
   ```

3. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Server**:
   ```bash
   python manage.py runserver
   ```

5. **Access the Webpage**:
   Open a browser and visit `http://127.0.0.1:8000/`.

---

#### Usage Instructions
1. Navigate to the webpage.
2. Enter a tweet into the input field and click the "Analyze" button.
3. View the sentiment analysis result:
   - A **smiling emoji 😊** will appear for **positive** tweets.
   - A **sad emoji 😢** will appear for **negative** tweets.

---

#### Future Enhancements
- **Live Twitter Analysis**: Extract and analyze tweets directly from Twitter using the Twitter API.
- **Neutral Sentiment Detection**: Enhance the model to classify tweets as neutral, positive, or negative.
- **Visualization**: Add graphical representations of sentiment analysis results.

---

#### Credits
- **Dataset**: Sentiment140 (https://www.kaggle.com/datasets/kazanova/sentiment140)
- **Framework**: Django
- **Model Training**: Custom model trained on Sentiment140 dataset.

---
### Demo
![image](https://github.com/user-attachments/assets/ccc55e49-30f1-4f91-bd55-b914a3fcd9cc)
![image](https://github.com/user-attachments/assets/be5139a6-502f-4f71-868b-421ca5db4534)
![image](https://github.com/user-attachments/assets/593c2210-c8e9-4036-878e-c8bf71e04c09)
![image](https://github.com/user-attachments/assets/e1677d68-727f-4796-8c29-2f74fe308c72)
![image](https://github.com/user-attachments/assets/f703d1b9-5bbc-4448-9327-40179672d20d)



Feel free to contribute or raise issues in the repository to make the project better! 🚀
