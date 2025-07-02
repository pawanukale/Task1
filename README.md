# Task1: Telemetry Data Formatter

This project solves a real-world IIoT (Industrial Internet of Things) data normalization problem for Daikibo Industries. The goal is to convert telemetry data from two different input formats into a unified format for further processing and analysis.

## 💡 Problem
Daikibo has two sets of IIoT devices streaming telemetry data:
- One format uses flat JSON with timestamp in milliseconds.
- The second format uses nested JSON with timestamp in ISO format.

## ✅ Solution
This script:
- Detects which format the data is in
- Parses and restructures fields like location and device info
- Converts ISO timestamps to milliseconds
- Returns a clean, unified JSON object as shown in `data-result.json`

## 🛠 Technologies Used
- Python 3
- Replit (cloud IDE)
- `unittest` for automated testing

## 📁 Files
- `data-1.json` – Input format 1
- `data-2.json` – Input format 2
- `data-result.json` – Expected unified format
- `main.py` – Python code to convert and test formats

## 🚀 How to Run
1. Run this project in [Replit](https://replit.com/)
2. Click **Run** – it will automatically execute test cases.
3. All tests must pass ✅

## 👨‍💻 Author
Pawan Ukale  
📧 pawanukale.22@stvincentngp.edu.in  
🔗 [GitHub Profile](https://github.com/pawanukale)
