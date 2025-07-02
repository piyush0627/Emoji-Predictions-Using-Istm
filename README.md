# 😄 Emoji Prediction using LSTM (Deep Learning)

This project predicts emojis based on text input using an LSTM-based deep learning model. The model is trained on pairs of text and corresponding emojis to learn emotional or semantic context from sequences of words.

---

## 📌 Objective

To build a model that can automatically suggest the most appropriate emoji based on the input sentence using Natural Language Processing and LSTM networks.

---

## 🧠 Technologies Used

- Python 3
- TensorFlow / Keras
- Numpy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## 📁 Dataset

A sample dataset contains text-emoji pairs such as:

| Text Input                  | Emoji |
|----------------------------|-------|
| I love pizza               | 🍕     |
| I'm feeling very happy     | 😄     |
| This is so sad             | 😢     |
| I can't stop laughing      | 😂     |
| It's raining outside       | 🌧️     |

You can create a `.csv` file or use a JSON format with:
```json
{
  "text": "I'm so tired",
  "label": "😴"
}
