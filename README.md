# MedExplain
A privacy-aware, verifiable AI health intelligence layer for automated medical report analysis

MedExplain transforms complex medical reports into simple, actionable health insights while keeping user data private and secure.

---

## What It Does

- Upload a medical report (image/PDF)
- Extract key biomarkers such as Glucose, Cholesterol, and HbA1c
- Classify results as Normal, Borderline, or High
- Generate simple, patient-friendly explanations
- Highlight potential health risks
- Provide guidance for doctor consultation

---

## Core Approach

- Smart Extraction: We are exploring coordinate-based OCR techniques to better map parameters with their corresponding values.
- Deterministic Inference Engine: Instead of black-box AI, the system uses transparent, rule-based clinical logic for reliable and explainable results.
- Privacy-First Design: The system is designed to run locally, ensuring sensitive health data is not exposed to external servers.

---

## Future Direction (Verifiable AI)

- Integrate zkVerify to validate health insights without exposing raw medical data
- Enable verifiable inference, ensuring trust in system-generated results
- Explore privacy-preserving architectures for secure healthcare applications

---

## Roadmap (Ideathon Week)

- [x] Project Vision and Architecture
- [ ] OCR Extraction Pipeline (In Progress)
- [ ] Clinical Rule Engine (In Progress)
- [ ] Basic Health Insight Generation
- [ ] zkVerify Integration Research

---

## Tech Stack

- Vision: OpenCV, Tesseract OCR
- Backend: Python (Flask)
- Logic: Rule-based inference system

---

## Status

Prototype under active development.  
Core OCR and analysis pipeline currently being built.

---

## Note

This project is being developed as a hackathon prototype. The current focus is on building a working core system, with advanced features such as verifiable inference planned as future enhancements.
