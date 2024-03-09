# Network Anomaly Detector

## Overview

The Network Anomaly Detector is designed to enhance cybersecurity by detecting anomalies in network traffic. The application takes a `.pcap` file as input, analyzes the packets, and generates a comprehensive `.csv` report.

## Business Value

- **Improved Security:** Identify and respond to network anomalies to prevent potential cyber threats.
- **Operational Continuity:** Maintain uninterrupted operations, minimizing the risk of downtime.

## Time to Market

Quick and efficient deployment with modular design and easy integration.

## Innovation and Efficiency

Innovative machine learning models ensure high accuracy, leveraging advanced metrics for reliable anomaly detection.

## User Experience

Minimal UI for easy `.pcap` file uploads and detailed anomaly reports in a user-friendly format.

## X Factor

Exceptional metrics (Accuracy: 99.6%, Precision: 98.8%, Recall: 99.0%, F1 score: 98.9%) highlight effectiveness and adaptability.

## Dataset Used

- [UNSW-NB15 Dataset](https://www.kaggle.com/input/nsw-full/UNSW-NB15_2.csv)

## Algorithm Used

Random Forest Classifier for robust anomaly detection.

## Django Integration

Utilizes Django framework for web application development.

### Running the server
```
cd network_intrusion
python manage.py runserver
```
This will start a local server on http://127.0.0.1:8000/. There is a minimal UI where you can upload a pcap file and get an output report. An example pcap file can be found in `network_intrusion/intrusion/media`.
