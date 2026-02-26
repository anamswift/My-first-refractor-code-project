# ⚡ Refactor AI — Legacy Code Modernization Tool

> **Developed by ANAM**

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Flask](https://img.shields.io/badge/Flask-3.0-black?style=for-the-badge&logo=flask)
![HTML](https://img.shields.io/badge/HTML5-CSS3-orange?style=for-the-badge&logo=html5)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge)

---

## 🚀 About The Project

**Refactor AI** is an AI-powered web application that automatically transforms legacy Java and COBOL source code into clean, modern Python 3 — complete with documentation, unit test reports, and quality evaluation.

Many organizations struggle with maintaining legacy codebases written in outdated languages. Manual refactoring is slow, expensive, and error-prone. This tool solves that problem by automating the entire modernization process in seconds.

---

## ✨ Features

- 🐍 **Python Translation** — Converts legacy Java/COBOL to clean modern Python 3 with type hints
- 📋 **Auto Documentation** — Generates structured docs covering overview, methods, input/output, and migration notes
- ✅ **Unit Test Report** — Automated logic verification with coverage percentage and pass/fail results
- 📊 **Evaluation Report** — Quality scoring with readability analysis, static analysis, and final grade
- 📎 **File Upload** — Supports .java, .cob, .cbl, .txt file uploads
- 🎨 **Animated UI** — Purple/blue themed interface with animated SVG snake, spilling coffee mug, and glowing effects

---

## 🖥️ Screenshots

### Homepage
> Animated UI with yellow snake, tilting coffee mug with spilling coffee, ANAM developer badge, and purple/blue gradient background

### Output Panels
> 4 panels showing Python Output, Documentation, Unit Test Report, and Evaluation Report with Grade A+ scoring

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Python 3 | Backend language |
| Flask | Web framework |
| HTML5 / CSS3 | Frontend structure and styling |
| SVG Animations | Logo and visual effects |
| Jinja2 | Template engine |

---

## 📁 Project Structure

```
refactor-ai/
├── app.py                  ← Flask backend (main application)
├── requirements.txt        ← Python dependencies
└── templates/
    └── index.html          ← Frontend UI (animated interface)
```

---

## ⚙️ How To Run

### Step 1 — Clone the repository
```bash
git clone https://github.com/anamswift/refactor-ai.git
cd claude refactor ai
```

### Step 2 — Install dependencies
```bash
pip install -r requirements.txt
```

### Step 3 — Run the application
```bash
python app.py
```

### Step 4 — Open in browser
```
http://127.0.0.1:5000
```

---

## 💻 How To Use

1. Open the app in your browser
2. Paste your legacy Java or COBOL code into the text box
3. Or upload a `.java` / `.cob` / `.txt` file
4. Click **⚡ REFACTOR AND DOCUMENT CODE**
5. View results in 4 output panels instantly

---

## 📊 Output Panels Explained

| Panel | Description |
|---|---|
| 🐍 Python Output | Clean Python 3 translation with type hints and Pythonic conventions |
| 📋 Documentation | Structured report covering overview, methods, input/output, migration notes |
| ✅ Unit Test Report | Automated test results showing coverage % and logic parity verification |
| 📊 Evaluation Report | Quality score, readability grade, static analysis, final score out of 100 |

---

## 🧪 Test It With This Java Code

```java
public class Calculator {
    public int add(int a, int b) {
        return a + b;
    }
    public int subtract(int a, int b) {
        return a - b;
    }
    public double divide(int a, int b) {
        if (b == 0) {
            System.out.println("Cannot divide by zero");
            return 0;
        }
        return (double) a / b;
    }
}
```

---

## 🔮 Future Work

- 🔌 Live AI API integration (Anthropic Claude / Google Gemini)
- 🌐 Support for more languages — COBOL, C++, PHP, Visual Basic
- 🧪 Real-time unit test execution and validation
- 👤 User authentication and project history dashboard
- 💾 Export results as PDF or Word document
- 🔌 VS Code and IntelliJ IDE plugin

---

## 👩‍💻 Developer

**ANAM**
- Built with passion for solving real-world software engineering problems
- Connect on LinkedIn

---

## 📄 License

This project is for educational purposes.

---

> *"From legacy Java to modern Python — automatically."* ⚡
