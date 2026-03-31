# can-bus-anomaly-detection-ids
Lightweight anomaly detection for CAN bus intrusion detection, focusing on signal behaviour analysis and practical deployment in resource-constrained environments.

---

## 🚗 Problem

Modern vehicles rely on CAN bus communication, which lacks authentication and encryption, making it vulnerable to attacks such as:

- Replay attacks
- Denial of Service (DoS)

Many existing solutions rely on complex transformations or heavy machine learning models, which are not suitable for resource-constrained ECUs.

---

## 💡 Solution

This project proposes a lightweight anomaly detection approach based on:

- Extracting key signal values from CAN data fields
- Measuring behavioural changes using standard deviation
- Detecting anomalies without requiring labelled datasets

The goal is to provide a **simple, efficient, and practical IDS** for automotive environments.

---
## 🧱 System Architecture

![Architecture](images/architecture.png)

## ⚙️ Implementation

- CAN traffic simulated using ICSim
- Replay and DoS attacks implemented
- Data extracted and processed from CAN frames
- IDS implemented in C
- Machine learning models evaluated in Python:
  - Random Forest
  - Decision Tree
  - MLP

---

## 📊 Results

- Replay Attack Detection: ~96.9%
- DoS Attack Detection: ~95.1%
- Random Forest Accuracy: ~96%

Key observation:
Replay attacks remain more difficult to detect compared to DoS attacks.

---

## 🧠 Key Insight

Lightweight signal-based anomaly detection can achieve competitive performance without relying on complex or computationally expensive models.

This highlights an important trade-off between detection accuracy and real-world deployability in automotive systems.

---

## 📎 Project Structure (coming soon)

- Source code
- Dataset samples
- Results and visualisations
- Full thesis document

---

## 📄 Full Thesis

(coming soon)
