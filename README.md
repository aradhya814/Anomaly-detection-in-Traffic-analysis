
# 🚦 Anomaly Detection in Traffic Sensor Data

This is a mini-project for the Big Data Analytics (BDA) course, focusing on real-time anomaly detection in urban traffic sensor data using machine learning models. The pipeline utilizes Apache Kafka for streaming, PySpark for processing, and models like Isolation Forest and XGBoost for classification.

---

## 📁 Project Structure

```
📁 anomaly-detection-traffic
│
├── notebooks/
│   └── Anomaly detection in Traffic analysis.ipynb   # Main code and model pipeline
│
├── reports/
│   └── BDA-mini-project-report.pdf                   # Final PDF report with methodology and results
│
├── scripts/
│   ├── kafka_producer_consumer.py                    # Kafka producer & consumer setup
│   ├── isolation_forest.py                           # Isolation Forest model code
│   └── xgboost_model.py                              # XGBoost model code
│
├── data/
│   └── (data directory or links to dataset)
│
├── visualizations/
│   └── (ROC curves, heatmaps, anomaly plots)
│
├── requirements.txt                                  # Python dependencies
├── .gitignore                                        # Ignored files
└── README.md                                         # You're here!
```

---

## 🧠 Objective

To detect **traffic anomalies** such as congestion, unusual patterns, or road incidents in real-time by applying machine learning models to traffic sensor data.

---

## 📊 Tools & Technologies

- **Apache Kafka** – Real-time streaming and message brokering  
- **PySpark** – Scalable data processing  
- **Pandas & NumPy** – Data manipulation  
- **Plotly & Seaborn** – Visualizations  
- **Isolation Forest** – Unsupervised anomaly detection  
- **XGBoost** – Supervised learning for classification  
- **METR-LA Dataset** – Traffic sensor dataset from Los Angeles

---

## 🛠️ Installation & Setup

1. **Clone this repository**
   ```bash
   git clone https://github.com/your-username/anomaly-detection-traffic.git
   cd anomaly-detection-traffic
   ```

2. **Create and activate a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. **Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run Apache Kafka locally or via Docker**  
   Ensure your Kafka producer is sending traffic data for model inference.

5. **Launch Jupyter Notebook**
   ```bash
   jupyter notebook
   ```

   Open `notebooks/Anomaly detection in Traffic analysis.ipynb` to explore the full pipeline.

---

## 📌 Highlights

- **Kafka Streaming Simulation** of live traffic data.
- **Anomaly Detection Pipeline** using Isolation Forest and XGBoost.
- **ROC Curve Analysis**, precision-recall metrics, and confusion matrix.
- **Visual representation** of anomalies over time using time series plots and heatmaps.
- **Report** with detailed methodology, model evaluation, and future improvements.

---

## 📄 Report

You can find the detailed project write-up in  


---

## 📚 References

- [METR-LA Dataset](https://github.com/liyaguang/DCRNN)
- [Kafka + PySpark Integration](https://medium.com/@amrut.patil/streaming-data-from-apache-kafka-using-pyspark-a-practical-approach-160d3ee7ed2e)
- [XGBoost Documentation](https://xgboost.readthedocs.io/en/latest/)
- [Scikit-learn Isolation Forest](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)

---

## 📌 Future Improvements

- Deploy the solution on cloud (AWS/GCP)
- Integrate a real dashboard for traffic anomaly alerts
- Improve performance using deep learning models

---

## 📬 Contact

Feel free to reach out via GitHub Issues or email if you’d like to contribute or ask questions.
