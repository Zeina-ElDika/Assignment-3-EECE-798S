# Assignment-3-EECE-798S
# 🎁 GiftJoy — AI Gift Recommendation Agent

**GiftJoy** is an interactive AI-powered business assistant built with **Google Gemini**, **Gradio**, and **Python**.  
It represents a smart gift shop that recommends thoughtful gifts for different occasions based on user input such as event type, recipient, age, and budget.

---

## 🧠 Project Overview

GiftJoy acts as a **virtual concierge** for a boutique gift shop, using Gemini's generative and function-calling capabilities to:
- Interact naturally with customers.
- Collect relevant context (name, email, occasion, recipient, age, budget).
- Suggest curated gift ideas with explanations and price bands.
- Record customer interest or unanswered questions for follow-up.

This project demonstrates **AI-powered business automation** with an emphasis on user engagement, tool integration, and interface design.

---

## 🚀 Features

| Feature | Description |
|----------|-------------|
| 🎯 **Gift Recommendation Engine** | Uses Gemini’s natural language reasoning to propose personalized gift ideas. |
| 💬 **Interactive Chatbot** | Engages users through a colorful Gradio interface. |
| 🧰 **Function Calling (Tools)** | Records leads and logs unanswered business queries automatically. |
| 📄 **Business Identity Generation** | Auto-generates the gift shop’s business summary and PDF brochure. |
| ⚡ **Optimized for Speed & Stability** | Compact knowledge base, trimmed chat history, and diagnostic cells. |
| 🎨 **Custom UI Design** | Gift-themed gradient background, friendly tone, and onboarding prompts. |
| 🩺 **Built-in Diagnostics** | Includes test cells for API connectivity, function-call verification, and output inspection. |

---

## 🧩 Tech Stack

- **Python 3.10+**
- **Google Gemini (gemini-1.5-flash / -8b)**
- **Gradio** for interactive UI
- **FPDF** for PDF generation
- **Pandas** for lead & feedback logging
- **PyPDF** for parsing the business PDF
- **Jupyter / Google Colab** as runtime environment

---

## ⚙️ How to Run

1. **Open in Google Colab**
   - Upload `business_agent.ipynb` (or `GiftJoy_Diagnostics_Complete.ipynb`).
   - Run all cells in sequence (top → bottom).

2. **Set up your Gemini API key**
   - In the configuration cell:
     ```python
     GOOGLE_API_KEY = "YOUR_GEMINI_API_KEY"
     ```
   - Keep it private (never commit to GitHub).

3. **Launch the UI**
   - The notebook defines two UIs:
     - **Stable UI:** minimal, safe for testing responses.
     - **Colorful UI:** gradient theme, streaming text.

4. **Interact with the chatbot**
   - Start by typing “Hello”.
   - The bot will ask:
     - Your **name**
     - The **occasion** (birthday, anniversary, etc.)
     - The **recipient** (friend, partner, child…)
     - Their **age**
     - Your **budget**
   - Then it will suggest relevant gifts 🎁

---



