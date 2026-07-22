# 🛒 AI Shopping Agent

An AI-powered shopping assistant built using **LangChain**, **Groq**, **Gemini Vision**, **SQLite**, and **Streamlit**.

The agent can search products, analyze uploaded product images, retrieve customer ratings, and place orders using tool calling.

---

## Features

- Search products from a SQLite database
- Retrieve product ratings
- Search products using an uploaded image (Gemini Vision)
- Place orders through an AI agent
- Built using LangChain tool-calling agents
- Interactive Streamlit interface

---

## Tech Stack

- Python
- LangChain
- Groq LLM
- Google Gemini Vision
- SQLite
- Streamlit

---

## Project Structure

```
shopping-agent/
│── app.py
│── shopping_agent.py
│── reviews_api.py
│── store.db
│── requirements.txt
│── README.md
│── .env.example
└── assets/
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
cd shopping-agent
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate it.

Windows:

```bash
.venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Environment Variables

Create a `.env` file using `.env.example`.

```
GROQ_API_KEY=your_groq_api_key
GOOGLE_API_KEY=your_google_api_key
```

---

## Run the Application

```bash
streamlit run app.py
```

---

## Example Capabilities

- Search for products by description
- Filter by price and organic status
- View product ratings
- Upload a product image to find similar products
- Place orders using natural language
