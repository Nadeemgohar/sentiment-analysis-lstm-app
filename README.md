# 📊 Sentiment Analysis Web Application

An **interactive AI-powered web application** built with **Streamlit** that predicts the **sentiment of text** as positive or negative.  
This app supports **both Machine Learning and Deep Learning models** for sentiment analysis.

---

## 🚀 Live Demo  
🔗 https://sentiment-analysis-lstm-app-fa9r4xnds4vpvrqetysnmx.streamlit.app/

## 🚀 Video Demo  
[Screencast from 2026-07-15 01-48-36.webm](https://github.com/user-attachments/assets/0cf7ec87-7060-42e9-8cb1-7670c68f5987)


---

## 📌 Features  
- **Predict Sentiment**: Detects whether text is positive or negative.  
- **Dual Model Support**: Choose between:
  1. Machine Learning model (`.pkl`)  
  2. Deep Learning model (`.keras`)  
- **Interactive UI**: Simple input form for entering text.  
- **Confidence Score**: Displays prediction probability for better insights.  
- **User-friendly Interface**: Built using Streamlit with sidebar options.  
- **Portfolio Links**: About Me section included in sidebar.  

---

## 🔍 Usage  
1. Open the app in your browser.  
2. Select a model from the sidebar:  
   - **Machine Learning Model (.pkl)**  
   - **Deep Learning Model (.keras)**  
3. Enter your text in the input area.  
4. Click **Predict**.  
5. The app will display:  
   - Sentiment: 😊 Positive / ☹️ Negative  
   - Confidence Score (0–1)  


## ⚙️ Tech Stack  
- **Python 3.9+ -- 3.11**  
- **Streamlit** (Web App)  
- **NumPy & Pandas** (Data Processing)  
- **TensorFlow / Keras** (Deep Learning Model)  
- **Scikit-learn & Joblib** (Machine Learning Model & Serialization)  

---

## 📄 How It Works  
- The text is **preprocessed using a tokenizer**.  
- Converted to **sequences** and **padded** to match model input.  
- The selected model predicts the **sentiment score**.  
- Score > 0.5 → Positive sentiment; Score ≤ 0.5 → Negative sentiment.  

---

## 👨‍💻 Author  
**Nadeem Gohar**  

- 💼 [LinkedIn](https://www.linkedin.com/in/nadeem-gohar-0708382b0/) 
- 💻 [GitHub](https://github.com/Nadeemgohar)  


---

## ⚠️ Disclaimer  
This project is for **educational purposes only**.  
It is not intended for commercial use but demonstrates **text-based sentiment analysis with AI**.  

---

## 📄 License  
This project is open-source and available under the **MIT License**.  

---
