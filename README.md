# 🚢 Dark Vessel Detection using AIS & Satellite Data

## 📌 Overview

This project focuses on detecting **suspicious maritime behavior (dark vessels)** using AIS (Automatic Identification System) data combined with satellite detections.

The system identifies vessels that may be:

* Disabling AIS signals
* Moving with abnormal speeds
* Exhibiting suspicious movement patterns

It combines **rule-based detection + machine learning + clustering + real-time simulation**.

---

## 🧠 Key Features

* AIS data preprocessing & cleaning
* Suspicious behavior detection:

  * AIS gaps detection
  * Speed anomalies
  * Movement jumps
* Risk scoring system
* Vessel clustering (KMeans)
* Machine Learning model (Random Forest)
* Explainability (why vessel is suspicious)
* Real-time alert simulation
* Geographic hotspot detection
* Interactive map visualization

---

## ⚙️ Tech Stack

* Python
* Pandas / NumPy
* Scikit-learn
* Matplotlib
* Folium (maps)

---

## 📊 Pipeline

1. Data Loading (AIS + Satellite)
2. Data Cleaning & Validation
3. Feature Engineering:

   * Time gaps
   * Speed anomalies
   * Distance jumps
4. Risk Scoring
5. Clustering vessels by behavior
6. Machine Learning prediction
7. Alert generation
8. Visualization (maps + charts)

---

## 📍 Results

* Total vessels analyzed: **13,716**
* High activity vessels: **4,511**
* Maximum risk score: **18**
* Detected suspicious geographic hotspots
* Real-time alert system successfully simulated

---

## 🌍 Visualization

The system provides:

* Global suspicious vessel map
* Hotspot detection areas
* Risk distribution plots

---

## 📁 Project Structure

```
dark-vessel-detection/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── data/
│   └── sample_data.csv
└── images/
    └── map.png
```

---

## 📦 Data

Due to large size, the full dataset is not included.

You can download similar datasets from:

* https://marinecadastre.gov/ais/
* https://globalfishingwatch.org/
* https://sentinel.esa.int/

Place data inside:

```
/data/
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
```

Open the notebook and run all cells.

---

## 💡 Example Output

* Risk scores per vessel
* Suspicious vessel ranking
* Real-time alerts
* Geographic hotspots
* Clustered vessel behaviors

---

## 🔍 Explainability

Each vessel is assigned a reason for being flagged, such as:

* AIS signal gaps
* Abnormal speed
* Suspicious movement jumps

---

## 📡 Future Improvements

* Real-time streaming integration
* Deep learning for trajectory prediction
* Satellite image-based detection (CV models)
* API deployment

---

## 👩‍💻 Author

Developed as an AI project for detecting suspicious maritime activity.

---

## ⭐ Notes

This project is designed to be **research-safe** and focuses on anomaly detection rather than enforcement systems.
