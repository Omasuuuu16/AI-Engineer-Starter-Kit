# AI Engineer Starter Kit

A beginner-friendly AI engineering project built as part of the **Helwan Career Center – 12-Week Industry Roadmap**.

This project demonstrates the fundamentals of working with **Python**, **REST APIs**, and **Hugging Face Transformers** by retrieving data from a public API and analyzing it using a pre-trained sentiment analysis model.

---

## 📌 Project Overview

The notebook performs the following tasks:

* Connects to a public REST API using the `requests` library.
* Retrieves a random joke in JSON format.
* Extracts the joke text.
* Loads a pre-trained Hugging Face sentiment analysis model.
* Predicts whether the text has a **Positive** or **Negative** sentiment.
* Displays the prediction along with the confidence score.

Additionally, the notebook includes sentiment analysis for a set of sample sentences to demonstrate the use of the `pipeline()` API.

---

## 🛠️ Technologies Used

* Python 3
* Jupyter Notebook
* Requests
* Hugging Face Transformers
* PyTorch

---

## 📂 Project Structure

```text
AI-Engineer-Starter-Kit/
│
├── starter_kit.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/your-username/AI-Engineer-Starter-Kit.git
cd AI-Engineer-Starter-Kit
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the notebook

Open `starter_kit.ipynb` using Jupyter Notebook or VS Code and run all cells from top to bottom.

---

## 📊 Example Output

```text
Joke:
Why did the chicken cross the road?

Punchline:
To get to the other side.

Sentiment: POSITIVE
Confidence: 99.84%
```

---

## 🎯 Learning Objectives

This project demonstrates:

* Working with REST APIs
* Handling JSON responses
* Using the `requests` library
* Loading pre-trained Hugging Face models
* Running sentiment analysis with `pipeline()`
* Building a reproducible Python project

---

## 📚 Dependencies

All required packages are listed in `requirements.txt`.

---

## 👨‍💻 Author

**Omar Mohamed**

Computer Science Student
Faculty of Computers and Artificial Intelligence, Helwan University

---

## 📄 License

This project was created for educational purposes as part of the Helwan Career Center AI Engineering roadmap.
