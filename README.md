# Fyre-Bill
Ai Writer
https://g.co/gemini/share/da75a8afe390
# 🔥 FYRE Bill Platform

FYRE Bill is an **AI-powered civic engagement tool** that empowers everyday citizens to draft, understand, and advance legislative bills.  

Built with **Banana API** as the primary AI engine and **Google Gemini** as a fallback, the platform makes the bill creation process faster, more accessible, and professional.  

---

## ✨ Features

- **Bill Generator (AI-Powered)**
  - Enter your state, topic, and bill details
  - Generates a polished, professional-quality bill draft
  - Uses **Banana API** (primary) and **Gemini** (fallback) for generation

- **Education Hub**
  - Explains your rights as a citizen
  - Walks through the lifecycle of a bill
  - Helps users understand how to move their idea forward

- **Find Your Representatives**
  - A lookup tool (coming soon) to connect citizens with their state and local reps
  - Drafted bills can be sent directly to the appropriate representative

---

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **AI Integration**:
  - [Banana API](https://banana.dev/) – primary AI generation
  - [Google Gemini](https://ai.google.dev/) – backup AI generation
- **Design**: Burnt orange + black theme with FYRE Army branding

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR-USERNAME/fyre-bill.git
cd fyre-bill
2. Add API Keys

Open index.html and replace placeholders with your keys:
const BANANA_API_KEY = "YOUR_BANANA_API_KEY";
const genAI = new GoogleGenerativeAI("YOUR_GEMINI_API_KEY");
Important: For production, don’t hardcode keys into client-side code.
Instead, use a backend proxy to keep keys secure.

3. Run the App

Open index.html in your browser.
No build step required — it’s a static HTML/JS app.

Project Structure
fyre-bill/
│── index.html       # Main app file
│── README.md        # Project documentation
│── assets/          # (optional) images, logo, etc.
Roadmap

 Representative lookup (API integration)

 Save and export bills as PDF

 Collaboration tools for community bill drafting

 Mobile app version

 Backend key management for security

👤 Author

Creator: FYRE Army

Lead Developer: CryptoHighway84

⚖️ License

MIT License – free to use, modify, and distribute.
🔥 “Turning citizens into lawmakers.”
