### 🧠 **Project Overview**

The project involves **classifying user questions into one of ten predefined categories** using machine learning, with a focus on **Natural Language Generation (NLG)**. You are working with a dataset of **2169 labeled questions**, evenly distributed among **10 classes (labels 0–9)**.

---

### 📊 **Dataset**

* **Format:** CSV with two columns: `text` (question), `label` (category).
* **Size:** 2169 questions.
* **Goal:** Predict the correct label for a new question based on its text.

---

### 🛠️ **Approach**

You explored various ML classification models and chose **Logistic Regression** with **TF-IDF vectorization** due to:

* Dataset size (small)
* Balanced classes
* Simplicity and interpretability
* Good performance for multi-class text classification

---

### 🧪 **Implementation Highlights**

* Preprocessing: Handled missing values and vectorized text using **TF-IDF** with `max_features=5000`.
* Model: Trained a **Logistic Regression** model (`max_iter=1000`).
* Evaluation: Achieved **91% accuracy** on the test set.
* Additional insights: Used a **confusion matrix** and **classification report** for evaluation.

---

### 💡 **Use Case**

This model could be used in real-world applications like:

* **Chatbots**: Automatically classifying incoming user queries into relevant categories.
* **Customer support**: Routing queries to the right department.
* **Helpdesk systems**: Automating question triage.

---

### 🔁 **Future Improvements**

* Collect more and better-balanced training data.
* Experiment with advanced NLP techniques: **n-grams**, **lemmatization**, **word embeddings**.
* Try **deep learning models** like **BERT** for richer semantic understanding.
* Use **ensemble models** to reduce misclassification.
* Apply **data augmentation** to boost underrepresented labels.
