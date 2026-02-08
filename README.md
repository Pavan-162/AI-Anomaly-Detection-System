# AI-Driven Anomaly Detection System (Network Security)

An unsupervised Machine Learning solution designed to identify irregular patterns in network traffic to detect potential security threats and system intrusions in real-time.

## 🚀 Overview
Traditional security systems rely on "rules." This project uses **Isolation Forest** algorithms to detect "unknown-unknowns"—anomalies that haven't been seen before. Developed as a 3-day rapid-deployment MVP.

## 🛠️ Tech Stack
- **Language:** Python
- **AI/ML Library:** Scikit-Learn (Isolation Forest)
- **Data Handling:** Pandas & NumPy
- **Dashboard:** Streamlit (Web UI)
- **Visualization:** Matplotlib / Seaborn

## 📊 Key Features
- **Unsupervised Learning:** No labeled data required to start detecting threats.
- **Dynamic Thresholding:** Adjustable 'contamination' rates to minimize False Positives.
- **Real-Time Dashboard:** Interactive interface for security analysts to upload logs and visualize risk scores.

## 📈 Impact
- Reduced manual log review time by automating the detection of outliers.
- Provides a scalable framework for monitoring high-frequency network packets.
