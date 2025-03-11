# LSTM-DefenseTextGen
# **Next Word Predictor for DRDO Defense Science Journal Subset**

## **Project Overview**  
This project is a **Next Word Prediction Model** trained on a subset of the **DRDO Defense Science Journal** dataset, specifically from the paper:  
**"Predictive Factor Analysis of Air-to-Air Engagement Outcomes Using Air Combat Manoeuvring Instrumentation Data."**  
The goal of this model is to **predict the next word** in a given sequence using an **LSTM-based neural network**.

## **Dataset**  
The dataset used for this project is derived from the **DRDO Defense Science Journal**, specifically from the paper mentioned above. The text corpus was processed and tokenized to train the model effectively.

## **Features**  
- 🚀 Uses **Long Short-Term Memory (LSTM)** networks to capture the context of input sequences.  
- 📖 **Trained on the DRDO Defense Science Journal subset**, ensuring domain-specific predictions.  
- 🔠 Implements **embedding layers** for word vector representation.  
- ⚡ Supports **real-time next-word prediction** for scientific and defense-related text.  
- 🛠️ Utilizes **Keras and TensorFlow** for deep learning implementation.  

## **Usage**  

### **Training the Model**  
1. Load the dataset (**DRDO Defense Science Journal subset**).  
2. Preprocess the text (**tokenization, padding**).  
3. Train the **LSTM model** on the processed data.  
4. Save the trained model for future use.  

### **Running Predictions**  
To generate the next-word prediction:  
1. **Load the trained model.**  
2. **Input a partial sentence.**  
3. **The model predicts the most probable next word.**  

## **Model Architecture**  
- **📌 Embedding Layer**: Converts words into dense vectors of fixed size.  
- **📌 LSTM Layer**: Captures long-term dependencies in text.  
- **📌 Dropout Layer**: Prevents overfitting by randomly deactivating neurons.  
- **📌 Dense Output Layer**: Uses a softmax activation to predict the next word.  

## **Potential Enhancements**  
- 🔍 **Fine-tuning** with a larger dataset.  
- 🤖 Implementing **Transformer-based models** (e.g., GPT or BERT) for improved accuracy.  
- 🌐 Developing a **web-based interface** for real-time next-word prediction.  

---
