# SQL Injection Detection Tool

## 📌 Overview
This Python script analyzes SQL queries for potential **SQL injection vulnerabilities** using regular expressions.  
It provides immediate console feedback and logs results to a CSV file (`results.csv`) for later review.

The tool:
- Detects suspicious SQL patterns (e.g., `UNION`, `OR 1=1`, comments, DDL/DML operations).
- Suggests secure coding practices to mitigate vulnerabilities.
- Marks queries as **SAFE** or **VULNERABLE**.
- Logs analysis results to a CSV file with details and suggested fixes.

---

## ⚙️ Features
- **Real-time analysis**: Prints results to the console as queries are tested.
- **Regex-based detection**: Identifies common SQL injection patterns.
- **Fix suggestions**: Provides actionable recommendations (e.g., parameterized queries, input validation).
- **CSV logging**: Saves query analysis results for documentation and auditing.

---

## 🛠️ Requirements
- Python 3.x
- Standard libraries: `re`, `csv`

No external dependencies are required.

---

## 🚀 Usage
1. Clone or download this repository.
2. Run the script:
   ```bash
   python sqlinjectiondetection.py
