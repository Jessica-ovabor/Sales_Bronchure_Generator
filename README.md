# 🧾 Sales Brochure Generator

This project is a **Sales Brochure Generator** built with **Python** and **OpenAI**.
It takes content from a website, applies **one-shot prompting** and **system prompts**, and generates a polished sales brochure using an AI model.


---

## 📌 Project Description

The **Sales Brochure Generator** is a Python-based application that leverages the **OpenAI API** to automatically create high-quality sales brochures from raw product or company information. Using **system prompts** and **one-shot prompting**, the tool ensures consistent tone, structure, and persuasive marketing language.

The project extracts content from websites using **BeautifulSoup**, cleans and summarizes the data, and feeds it into an AI model to generate polished, ready-to-use brochure copy. Dependency management is handled with **uv**, and sensitive configuration is managed securely using **python-dotenv**.

This project demonstrates practical use of prompt engineering, API integration, and text generation for real-world marketing automation.

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

* **Python 3.11.8**
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

> Make sure `uv` is installed:

```bash
pip install uv
```
> Install project dependencies:

```bash
uv sync
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
├── extractor.py
├── bronchure.ipynb

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
* Adjust system and user prompts for different brochure styles
* Test with various website contents for best results

---

## 📄 License

This project are for my **LLM personal portfolio**.
You are free to modify and expand it.

---

