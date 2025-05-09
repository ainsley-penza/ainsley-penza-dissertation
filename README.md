# 📄 Invoice Data Extraction using Machine Learning 🚀

**A Bachelor's Degree Dissertation Project** **Malta College of Arts, Science and Technology (MCAST)**

**Author:** Ainsley (ainsley.penza.f32061@mcast.edu.mt)  
**Supervisor:** Mr. Alan Gatt  
**Project Status:** In Progress

---

## 🌟 Overview

This project tackles the challenge of **automating data extraction from invoices**. Manual entry is a drag – it's slow, error-prone, and frankly, not the best use of anyone's time. This dissertation, for the Malta College of Arts, Science and Technology (MCAST), explores a Machine Learning pipeline to digitize this process efficiently. I'm using the power of **YOLOv12 for object detection** and **Tesseract OCR for text recognition** to transform invoice images into clean, structured JSON data.

---

## 🎯 Project Aims & Objectives

The core mission is to design, build, and test a robust ML system for extracting key information from invoices.

* **Dataset Curation:** Assemble and meticulously annotate a diverse set of invoice images.
* **Element Detection:** Train a **YOLOv12 model** to accurately pinpoint essential invoice fields (like invoice numbers, dates, totals, line items, etc.).
* **Text Extraction:** Employ **Tesseract OCR** to "read" the text within the detected regions.
* **Structured Output:** Convert the extracted data into a developer-friendly **JSON format**.
* **Performance Evaluation:** Rigorously assess the system's accuracy and efficiency.