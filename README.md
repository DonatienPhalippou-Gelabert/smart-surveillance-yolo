# Smart Surveillance: Silhouette-based Classification (R&D POC)

## Project Overview
This repository contains the Proof of Concept (POC) developed during an industrial R&D mission for Technopool. 

The Challenge: Enhance safety in private swimming pool environments by developing a smart surveillance system. The core requirement was to distinguish between adults and children in real-time to trigger appropriate safety alerts.

---

## Key Features
* Real-time Object Detection: Leveraging the YOLO (You Only Look Once) architecture for high-speed and accurate person detection.
* Biometric Classification: Implementation of a custom logic based on limb-length analysis and body ratios to differentiate adults from children.
* Industrial Scoping: Conducted the full lifecycle from business requirement gathering to technical specification.
* Robustness Evaluation: Tested the model against various environmental constraints (lighting, camera angles, weather conditions) for future embedded deployment.

---

## Technical Stack
* Language: Python 3.x
* AI Frameworks: YOLO (Ultralytics), OpenCV
* Data Analysis: NumPy, Matplotlib
* Tools: Git, Visual Studio, Shell scripting
* Methodology: Agile R&D / Prototyping

---

## Project Structure
```text
├── data/               # Project documentation & sample formats
├── models/             # YOLO configuration and weight references
├── notebooks/          # Exploratory Data Analysis & Model Evaluation
├── src/                # Source code for detection and classification
├── requirements.txt    # Python dependencies
└── README.md           # Project showcase
```
---

## Impact & Results
* Successful POC: Delivered a working prototype demonstrating the feasibility of biometric-based age group classification.
* Strategic Roadmap: Provided Technopool's decision-makers with a technical report on hardware requirements and scalability for industrialization.
* Optimization: Identified key body-ratio markers that improved classification accuracy compared to simple height-based triggers.

---

## Author
Donatien Phalippou-Gelabert
* Ingénieur Civil des Mines (Saint-Étienne)
* Master in Applied Mathematics (MAEA)
* LinkedIn: https://www.linkedin.com/in/donatien-phalippou-gelabert-31707a237/

---
Note: This repository contains the methodology and anonymized architecture of the project. Proprietary data and specific business logic have been removed for confidentiality.
