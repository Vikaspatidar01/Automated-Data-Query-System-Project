# Automated Data Query and Retrieval System

This project is an offline, automated system for querying structured product data using natural language. It leverages **MongoDB**, **CSV** files, and a local or fallback **open-source LLM (Large Language Model)** like Facebook’s `opt-125m` for natural language to MongoDB query conversion.

## 📌 Features

- ✅ Load structured product data from a CSV file into MongoDB.
- ✅ Use natural language queries to retrieve product insights.
- ✅ Run predefined test cases to validate query accuracy.
- ✅ Automatically convert user queries to MongoDB queries.
- ✅ Save query results to a CSV file.
- ✅ Display queries and results in a user-friendly format.
- ✅ Works completely offline with open-source LLMs.

---

## 🗂️ Technologies Used

- **Python 3**
- **MongoDB**
- **Transformers (Hugging Face)**
- **Facebook OPT 125M (fallback model)**
- **Pandas**
- **Datetime, Regex, JSON, CSV**

---

## 🛠️ Setup Instructions

1. **Install Dependencies**

pip install pymongo pandas transformers torch accelerate
📍 Notes
This tool works offline and doesn't require cloud-based LLMs.

It uses fallback model facebook/opt-125m if a heavier model cannot load.

Make sure your CSV is properly formatted; bad data can cause processing issues.

## 🙌 Acknowledgements
Hugging Face Transformers & Facebook OPT models

MongoDB Community

Python open-source libraries

## 👤 Author
Vikas Patidar

Data Scientist (Certified by IOTA Academy Indore)

BCA, Govt Holkar Science College Indore

Skills: Python, MongoDB, LangChain, LlamaIndex, Data Analysis, Machine Learning
