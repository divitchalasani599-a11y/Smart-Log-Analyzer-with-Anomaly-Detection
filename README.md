# 🧠 Smart Log Analyzer with Anomaly Detection

A Python-based Smart Log Analyzer that processes system log files, detects unusual activity patterns, and identifies anomalies using statistical analysis.

---

## 📌 Project Overview

The Smart Log Analyzer is designed to analyze large system or server log files and detect abnormal behavior patterns.

It parses log entries, extracts relevant information (IP, timestamp, request type), generates statistics, and detects anomalies based on threshold and frequency analysis.

This project demonstrates log processing, data analysis, and anomaly detection techniques.

---

## 🎯 Objective

- To parse and analyze server log files.
- To generate request statistics.
- To detect suspicious activity patterns.
- To identify high-frequency abnormal IP access.
- To apply anomaly detection techniques.

---

## ✨ Features

- 📄 Log file parsing  
- 🌐 IP-based request analysis  
- 📊 Request frequency statistics  
- 🚨 Suspicious activity detection  
- 📝 Anomaly reporting  
- 📈 Visualization support  

---

## 🛠 Technologies Used

- Python  
- Pandas  
- Regular Expressions (re)  
- Collections  
- Matplotlib  

---

## ⚙ Installation

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/smart-log-analyzer.git
cd smart-log-analyzer
```

---

### 2️⃣ Install Dependencies

```bash
pip install pandas matplotlib
```

---

## ▶ Usage

```bash
python log_analyzer.py
```

---

## 📂 Project Structure

```
smart-log-analyzer/
│
├── log_analyzer.py
├── anomaly_detector.py
├── sample.log
├── requirements.txt
└── README.md
```

---

## 🔄 How It Works

1. Load log file.
2. Extract IP addresses and request details.
3. Count request frequency per IP.
4. Detect abnormal request spikes.
5. Generate anomaly report.

---

## 📊 Example Output

```
Top IP Addresses:
192.168.1.10 → 120 requests
10.0.0.5 → 95 requests

⚠ Suspicious Activity Detected:
192.168.1.10 exceeded threshold limit.
```

---

## 🚀 Future Enhancements

- Real-time log monitoring
- Machine learning-based anomaly detection
- Web dashboard
- Email alert integration
- Cloud deployment

---

## 👨‍💻 Developer

Divit Chalasani  

---

## 📄 License

This project is developed for academic and system analysis purposes.
