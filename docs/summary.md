# CAN Bus Anomaly Detection – Summary

This project explores intrusion detection for Controller Area Network (CAN bus) systems used in vehicles.

## Problem
CAN bus lacks authentication and encryption, making it vulnerable to attacks such as replay and denial of service.

## Approach
A lightweight anomaly detection method was used based on signal behaviour analysis (standard deviation), supported by machine learning models.

## Attacks Tested
- Replay attack
- Denial of Service (DoS)

## Results
- Replay detection: ~96.9%
- DoS detection: ~95.1%
- Random Forest: ~96%

## Key Insight
Lightweight detection can still provide strong performance while being suitable for resource-constrained automotive environments.
