# 🧾 Sales Brochure Generator (OpenAI + Python)

This project is a **Sales Brochure Generator** built with **Python** and **OpenAI**.
It takes content (optionally scraped from a website), applies **one-shot prompting** and **system prompts**, and generates a polished sales brochure using an AI model.

---

## ✨ Features

* Uses **OpenAI** for brochure generation
* Supports **one-shot prompting**
* Uses **system + user prompts**
* Web content extraction with **BeautifulSoup**
* Environment variable management with **python-dotenv**
* Fast dependency management using **uv**

---

## 🛠 Tech Stack

* **Python 3.10+**
* **OpenAI API**
* **uv** (package manager)
* **python-dotenv**
* **BeautifulSoup4**
* **requests**

---

## 📦 Installation

### 1️⃣ Clone the repository

```bash
git clone https://github.com/Jessica-ovabor/sales-brochure-generator.git
cd sales-brochure-generator
```

### 2️⃣ Install dependencies using `uv`

```bash
uv add openai python-dotenv beautifulsoup4 requests
```

> Make sure `uv` is installed:

```bash
pip install uv
```

---

## 🔑 Environment Setup

Create a `.env` file in the root directory:

```env
OPENROUTER_API_KEY=openrouter_api_key
OPENROUTER_BASE_URL=openrouter_base_url
```

⚠️ **Never commit your `.env` file to GitHub**

---

## 🚀 Usage
Select the right kernel on jupyter notebook:

```bash
select .venv as your current kernel
```
Run the main script on jupyter notebook:

```bash
bronchure.ipynb
```

### Example Workflow

1. Scrape product or company content using BeautifulSoup
2. Feed extracted text into OpenAI
3. Apply a **system prompt** to define tone and role
4. Use **one-shot prompting** for consistent brochure style
5. Extract the relevant links from OpenAI

---

## 📁 Project Structure

```text
app
├── app.py
├── link_extractor.py
├── bronchure.ipynb
├── .env
├── README.md
```

---

## 🧪 Example Output

* Catchy headline
* Clear value proposition
* Bullet-point features
* Strong call-to-action

---

## 🛡 Notes

* Ensure you have sufficient OpenAI API credits or use OpenRouter API free open source model
* Internet connection required
* Use responsibly and follow OpenAI usage policies

---

## 📄 License

This project is for **educational purposes**.
You are free to modify and expand it.

---

