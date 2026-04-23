# 🤖 AI Chatbot using PyTorch & NLP

A simple **AI-based chatbot** built using **PyTorch** and **Natural Language Processing (NLP)**.  
This chatbot can understand user input, classify it into predefined intents, and respond accordingly.

---

## 🚀 Features

- 🧠 Intent classification using Neural Network  
- 💬 Interactive command-line chatbot  
- 🔤 Text preprocessing using NLTK (tokenization & stemming)  
- 📊 Bag-of-Words model for input representation  
- ⚡ Lightweight and beginner-friendly  

---

## 🛠️ Technologies Used

- Python  
- PyTorch  
- NLTK  
- NumPy  

---

## 📂 Project Structure

```

pytorch-chatbot/
│
├── chat.py          # Run chatbot
├── train.py         # Train the model
├── model.py         # Neural network architecture
├── nltk_utils.py    # NLP helper functions
├── intents.json     # Dataset (intents & responses)
├── data.pth         # Trained model (generated after training)
└── README.md

```

---

## ▶️ How to Run

### 1️⃣ Install dependencies
```

pip install torch nltk numpy

```

---

### 2️⃣ Download NLTK data
```

python

> > > import nltk
> > > nltk.download('punkt')
> > > nltk.download('punkt_tab')

```

---

### 3️⃣ Train the model
```

python train.py

```

---

### 4️⃣ Run chatbot
```

python chat.py

```

---

## 💡 How it Works

1. User input is tokenized using NLTK  
2. Words are converted into Bag-of-Words vector  
3. Input is passed into a neural network  
4. Model predicts the intent  
5. Bot returns a predefined response  

---

## ⚠️ Limitations

- Works only on predefined intents  
- Cannot generate new responses  
- Limited conversational ability  

---

## 📈 Future Improvements

- Add Web Interface (Flask / React)  
- Use advanced NLP models (Transformers)  
- Improve dataset for better accuracy  

---

