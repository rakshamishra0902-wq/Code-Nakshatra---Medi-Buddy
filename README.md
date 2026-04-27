# 🩺 Medi-Buddy

## 📌 Description

Medi-Buddy is a pharmacogenomics-based web application that analyzes a user's genetic data to provide personalized medication insights.

Users upload their genetic file (VCF format), and the system processes it using backend analysis to predict drug response, dosage, and safety.

---

## 🚀 Features

- 📁 Upload genetic files (VCF format)  
- 🧬 Extract gene variants and pharmacogenomic data  
- ⚠️ Drug risk detection (Toxic / Ineffective / Safe)  
- 💊 Dosage recommendations  
- 🤖 AI-based alternative medicine suggestions  
- 📊 Result dashboard  
- 📄 Clinical report generation (PDF)  

---

## 🛠️ Tech Stack

### Frontend
- React + Vite  

### Backend
- Python FastAPI (high-performance API layer)  
- cyvcf2 (efficient VCF parsing)  
- LLM API (OpenAI / Gemini)  
- CPIC database (drug-gene guideline mapping)  

---

## ⚙️ How It Works

1. Upload genetic file (VCF)  
2. Backend validates file format and data  
3. Extract genetic variants and relevant genes  
4. Analyze drug response using pharmacogenomic rules  
5. Classify drugs:  
   - Safe ✅  
   - Toxic ❌  
   - Ineffective ⚠️  
6. Generate:  
   - Dosage recommendations  
   - Alternative medicines (AI)  
7. Display results on dashboard  
8. Generate clinical PDF report  

---

## 🧩 System Flow

User → Upload File → Backend Processing → Analysis Engine → Results Dashboard → Report Generation  

---

## 📊 Output

- Drug safety classification  
- Personalized dosage suggestions  
- AI-based alternative medications  
- Clinical PDF report  

---

## ⚠️ Disclaimer

This project is for educational and research purposes only and should not be used as a substitute for professional medical advice.

---

## 🤝 Contributing

Pull requests are welcome. Feel free to improve documentation, features, or UI.

---

## ⚠️ Note on Server Startup Time

The backend of this project is hosted on Render (free plan).

⏳ The server may take **50 seconds to 1 minute** to start on the first request.  
This delay happens because the service goes to sleep after inactivity.

👉 This is **not a bug or glitch** — it is expected behavior on Render's free tier.

Please wait for a minute if the app seems unresponsive initially.

##Application link

 medi-buddyy.netlify.app

##Project screenshots

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/87974d57-b05d-46eb-b677-ca1030425dc3" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/e899ebf2-8750-4872-bab7-733f0785130e" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/8326377f-d8ea-4a96-beeb-28400eb2ad72" />





