# vibration-condition-monitoring
Vibration-based condition monitoring and anomaly detection using CWRU bearing data, signal processing, FFT, RMS, and Isolation Forest.

# Vibration-Based Condition Monitoring and Anomaly Detection

## Overview

This project presents a vibration-based condition monitoring framework for identifying abnormal operating conditions in rotating machinery using signal processing and machine-learning-assisted anomaly detection techniques.

The analysis utilizes the Case Western Reserve University (CWRU) Bearing Data Center dataset and evaluates vibration behavior under normal, ball fault, and inner race fault conditions.

The project demonstrates methodologies commonly used in predictive maintenance and condition-monitoring applications.

---

## Objectives

The primary objectives of this project were:

- Analyze vibration measurements from rotating machinery
- Extract condition indicators from sensor data
- Compare healthy and fault-related operating conditions
- Apply frequency-domain analysis using Fast Fourier Transform (FFT)
- Implement machine-learning-assisted anomaly detection
- Demonstrate predictive maintenance concepts applicable to electromechanical systems

---

## Methods

The analysis incorporates:

- Root Mean Square (RMS) analysis
- Variance and standard deviation analysis
- Kurtosis-based condition indicators
- Fast Fourier Transform (FFT)
- Signal segmentation
- Threshold-based anomaly detection
- Isolation Forest anomaly detection

---

## Key Results

The study identified clear differences between healthy and degraded operating conditions.

| Condition | RMS Value |
|------------|------------|
| Normal | 0.0738 |
| Ball Fault | 0.1392 |
| Inner Race Fault | 0.2915 |

The results demonstrated increasing vibration energy and variability as fault severity increased.

The Isolation Forest model also identified substantially more anomalous segments in fault conditions than in the healthy baseline condition.

---

## Repository Structure

```text
docs/
    TechnicalReport_vibration_cm.pdf
    Project_Askhat_Colab.pdf

notebooks/
    Project_Askhat_2.ipynb

data/
    Dataset information

figures/
    Generated visualizations
