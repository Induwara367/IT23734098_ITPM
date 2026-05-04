# IT3040 – ITPM Assignment 1

## Transliteration Accuracy Testing (Option 1)

### 📌 Project Overview

This project is developed as part of the **IT3040 – IT Project Management (ITPM)** module. The main objective is to evaluate the accuracy of a Sinhala transliteration system that converts **chat-style Singlish input into Sinhala output**. 

The system under test:
👉 https://www.pixelssuite.com/chat-translator

---

### 🎯 Objective

* Identify **incorrect transliteration scenarios** in the system
* Design **50 negative test cases** covering Singlish input variations
* Automate testing using **Playwright**
* Analyze system weaknesses based on results 

---

### 🧪 Test Case Requirements

* Total **50 test cases**
* Must cover **24 Singlish input types**
* At least **2 test cases per type**
* Remaining cases can be from any category
* Only **negative test cases (failures)** are considered 

---

### 🗂️ Project Structure

```
├── test_automation/
│   ├── test_automation.py
│   ├── Assignment 1 - Test cases.xlsx
│   └── other supporting files
├── README.md
└── requirements (Playwright, openpyxl)
```

---

### ⚙️ Prerequisites

Before running the project, install:

* Python 3.11 or 3.12
* Google Chrome (recommended)
* Pip package manager

---

### 🔧 Installation Steps

Run the following commands in terminal:

```bash
pip install -U pip
pip install playwright openpyxl
playwright install
```

---

### ▶️ How to Run the Automation

Execute the Playwright script using:

```bash
python test_automation.py --excel "test_automation/Assignment 1 - Test cases.xlsx" --url "https://www.pixelssuite.com/chat-translator" --wait-ms 5000 --type-delay-ms 80 --slow-mo-ms 200 --save-every 1 --keep-open
```

This will:

* Automatically input test cases
* Capture actual outputs
* Update Excel file with results 

---

### 📊 Excel File Instructions

* Fill only:

  * TC ID
  * Input length type (S / M / L)
  * Input
  * Expected Output
* Do NOT fill:

  * Actual Output
  * Status

These will be auto-generated after running the script 

---

### ➕ Additional Columns

After execution, manually add:

* **Singlish Input Types Covered**
* **Evidence / Rationale**

---

### 🔍 Singlish Input Types Covered

The test cases include various input categories such as:

* Questions, Commands, Greetings
* Romanization Variants
* English word insertions
* Numbers, Currency, Dates, Time
* Slang, Emojis, Online identifiers
* Platform names (Zoom, WhatsApp)
  *(and more as defined in the assignment)* 

---

### 📦 Submission Requirements

* Playwright project (full source code)
* Excel file with test cases
* Public GitHub repository link
* All files renamed with registration number
* Submit as a ZIP file before deadline 

---

### ⚠️ Important Notes

* Repository must be **public**
* Plagiarism >10% will result in **zero marks**
* Do NOT use examples from given appendices

---

### 👨‍💻 Author

**Student Name:** (Your Name)
**Registration Number:** IT23734098

---

### 🚀 GitHub Repository

👉 https://github.com/Induwara367/IT23734098_ITPM

---

### 📌 Summary

This project demonstrates:

* Software testing skills
* Test automation using Playwright
* Real-world system evaluation
* Structured defect identification

---
