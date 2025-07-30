# Non-Invasive Diabetes Detection System

## Overview

This project proposes a **non-invasive blood glucose monitoring system** using **image processing** and **deep learning techniques** to overcome the pain, risk, and recurring cost associated with traditional finger-prick methods. It aims to enhance the convenience, accessibility, and compliance of diabetes monitoring for patients, especially in low-resource settings.

**Year**: 2022  
**Institution**: Sri Sivasubramaniya Nadar College of Engineering  
**Budget**: ₹14,000  
**Team Members**: Abbhinav E, Karthikeyan S, Oviasree S, Keerthick V  
**Faculty Mentor**: Dr. P. Mirunalini

---

## Objective

- To develop a non-invasive diabetes monitoring system using **laser-illuminated fingertip imaging** and **Convolutional Neural Networks (CNNs)**.
- To offer a reliable, painless, and cost-effective alternative for mass screening and regular glucose level monitoring.

---

## Problem Statement

Traditional glucose monitoring systems rely on invasive finger-prick tests, which are:
- Painful and uncomfortable for regular use
- Expensive due to consumables (test strips, lancets)
- Risky in terms of infection and cross-contamination
- Time-consuming and not user-friendly

---

## Proposed Solution

The system utilizes **Raspberry Pi hardware** and **CNN models** to perform real-time glucose level classification based on image analysis.

### Modules

1. **Image Capturing Module**  
   - A **Raspberry Pi Camera** captures high-resolution images of the fingertip under **675 nm laser illumination**.

2. **Feature Extraction Module**  
   - The **Raspberry Pi Zero** processes images to extract features such as intensity variation and light absorption patterns.

3. **Prediction Module**  
   - A **trained Convolutional Neural Network (CNN)** predicts blood glucose concentration from the extracted features.

---

## Hardware Architecture

- Raspberry Pi Zero (processor)
- Raspberry Pi Camera Module
- 675 nm Laser Light Source
- User Interface (for real-time prediction display)

---

## Novelty

- **Integration of Low-Cost Hardware with Deep Learning**  
  Uses Raspberry Pi and CNN models to provide a budget-friendly solution.

- **Laser-Illuminated Imaging**  
  Analyzes glucose-related light absorption through skin tissue using 675 nm wavelength.

---

## Features and Deliverables

- Portable, affordable, **non-invasive hardware device**
- Real-time glucose prediction with CNN-based classification
- User-friendly interface suitable for home and clinical use

---

## Impact

- **Improved Healthcare Accessibility**: Eliminates recurring costs, making glucose monitoring affordable for underserved populations.
- **Enhanced Patient Compliance**: Painless and portable monitoring encourages consistent usage and better diabetes management.

---

## Outcome

- Working prototype developed and demonstrated
- Potential for publication, commercialization, and further clinical validation
