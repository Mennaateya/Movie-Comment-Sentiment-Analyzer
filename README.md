# 🎬 Movie Comment Sentiment Analyzer

Ever scrolled through movie comments and thought,  
“Wait... is this person praising the movie or totally roasting it?”  
Well, we built a model to find out.

## 💡 The Idea

We wanted to build a simple yet powerful sentiment analysis model  
that can tell if a movie review is **positive** or **negative** — no guessing!

We used a dataset of 50,000 IMDb reviews and trained a deep learning model  
to read between the lines and understand the **real mood** behind the words.

## 🧠 The Model

Here’s what’s going on under the hood:

- **GloVe word embeddings** to capture word meanings.
- A **Bidirectional GRU** model — because understanding context from both sides of a sentence is 🔑.
- A final **Sigmoid layer** for binary classification: `Positive` or `Negative`.

## 🎯 The Results (We're proud, okay?)

After all the data cleaning, tuning, testing, and a bit of suffering  
(thanks, Colab GPU limits), we finally got:

**Test Accuracy**: `88.7%`  
**Test Loss**: `0.2748`

And yes, that’s a solid accuracy score — especially for a model we built from scratch,  
layer by layer, and refined manually till it hit just right.

## 🧰 Tech Stack

- Python 🐍  
- TensorFlow & Keras  
- GloVe (Global Vectors for Word Representation)  
- NLTK  
- NumPy & pandas  
- Scikit-learn  
- Matplotlib (for some cool visualizations)

## ⚙️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/Mennaateya/Movie-Comment-Sentiment-Analyzer.git
   cd Movie-Comment-Sentiment-Analyzer
   ```

2. Install the requirements:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run the model:

   ```bash
   jupyter notebook notebooks/sentiment_model_gru.ipynb
   ```
## 📊 Dataset
We used a publicly available dataset from Stanford (no worries, you won’t have to download anything yourself — we’ve got you covered).  
You'll find the link inside the notebook!

## 👩‍💻 Built With Love By
Menna   
Marym  
Farah  
Nada  
Basmalla  
Youstina  

## 📧 our Gmails:
mennaateya30@gmail.com
marym.ayman.mo@gmail.com
nadawahdan493@gmail.com 

## 🔗 LinkedIn profiles:

- Menna : https://www.linkedin.com/in/menna-ateya
- Marym : https://www.linkedin.com/in/marym-ayman-43aa0a26b
- Nada : https://www.linkedin.com/in/nada-wahdan-5227222b1
## 🪪 License
MIT License – feel free to use, modify, and share the project.
Just give credit where credit is due 🤝
