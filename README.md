# ⚡ Efficient Energy Calculator

Welcome to the **Efficient Energy Calculator**, an AI-powered web app designed to promote **energy awareness** and provide **smart suggestions** to help reduce energy consumption.

This project integrates a simple frontend with a Python Flask backend and utilizes the **Mistral-7B LLM** via the **OpenRouter API** to generate **energy-saving recommendations** based on user input.

---

## 📽️ Project Demo

▶️   Youtube video of how app works : https://youtu.be/lcgIanOIlL0?si=K4GbS2Y26-OQ_5MI

---

## 🧠 What the App Does

- Takes user input for:
  - Appliance name
  - Power rating (in Watts)
  - Usage time (in hours/day)
- Calculates estimated daily energy consumption (in kWh)
- Sends this data to an AI model (Mistral-7B via OpenRouter)
- Receives and displays personalized **energy-saving suggestions**
- Allows users to **export suggestions as a PDF**
- Simulated login interface for demo purposes

---

## 🛠️ Tech Stack

| Component  | Technology         |
|------------|--------------------|
| Frontend   | HTML, CSS, JavaScript |
| Backend    | Python, Flask      |
| AI Model   | Mistral-7B (via OpenRouter API) |
| PDF Export | jsPDF (JavaScript) |
| API Key    | Stored using `.env` file |

---

## 🚀 How to Run the App

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/efficient-energy-calculator.git
cd efficient-energy-calculator
pip install -r requirements.txt
OPENROUTER_API_KEY=your-api-key-here
python app.py
