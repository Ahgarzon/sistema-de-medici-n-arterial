# ⌚ Blood Pressure Measurement System (IoT + Python + Arduino)

This project proposes an **innovative method for measuring blood pressure** by integrating  
**Arduino sensors** with **Python data processing**. The system captures the **pressure curve**,  
processes pulses, applies diagnostics based on **WHO standards**, and automatically logs results  
to **Google Sheets**, enabling **remote monitoring** and real-time clinical traceability.

---

## 📌 Features
- Measurement of blood pressure with **electronic sensors** (Arduino).
- Data acquisition and processing with **Python**.
- **Automatic classification** of results based on WHO standards.
- Integration with **Google Sheets** for real-time cloud storage.
- Potential use for **remote healthcare** and **IoT-based clinical monitoring**.

---

## 🛠️ Tech Stack
- **Hardware:** Arduino  
- **Software:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, gspread (Google Sheets API)  
- **Domain:** IoT, Biomedical Signal Processing  

---

## 📂 Project Structure
├── CODIGO_PRESION_FUNCIONAL.ino # Arduino code for data acquisition
├── Interpretacion de Datos.py # Python script for processing and visualization
└── README.md

---

## 📊 Results
- Accurate pulse detection from pressure signals.
- WHO-standard classification (Normal, Pre-hypertension, Hypertension).  
- Real-time cloud data storage for clinical follow-up.

### Example Output  
*(Add a graph of the pressure curve or classification example if available)*

---

## 📥 Installation
1. Clone the repository:
```bash
git clone https://github.com/Ahgarzon/sistema-de-medici-n-arterial
cd sistema-de-medici-n-arterial
