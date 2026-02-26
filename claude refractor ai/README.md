# CodeMorph AI — Legacy Code Modernizer
### Developed by ANAM

---

## 📁 Project Structure

```
your_project/
├── app.py              ← Flask backend (main file)
├── requirements.txt    ← Python dependencies
├── .env.example        ← API key template
└── templates/
    └── index.html      ← Frontend UI
```

---

## 🚀 Setup in VS Code

### Step 1 — Install Python dependencies
Open VS Code terminal (Ctrl + backtick) and run:
```bash
pip install -r requirements.txt
```

### Step 2 — Set your Anthropic API Key

**Option A (Recommended) — Set environment variable:**

Windows (Command Prompt):
```
set ANTHROPIC_API_KEY=your-actual-key-here
```

Windows (PowerShell):
```
$env:ANTHROPIC_API_KEY="your-actual-key-here"
```

Mac/Linux:
```
export ANTHROPIC_API_KEY=your-actual-key-here
```

**Option B — Edit app.py directly:**
Find this line in app.py:
```python
client = anthropic.Anthropic(api_key=os.environ.get("ANTHROPIC_API_KEY", "your-api-key-here"))
```
Replace `"your-api-key-here"` with your actual key.

Get your API key from: https://console.anthropic.com

### Step 3 — Run the app
```bash
python app.py
```

### Step 4 — Open in browser
Go to: http://127.0.0.1:5000

---

## ✅ How to use
1. Paste your Java or COBOL code in the text area (or upload a file)
2. Click "REFACTOR & DOCUMENT CODE"
3. View the translated Python code and auto-generated documentation

---

## ❗ Common Issues

| Problem | Fix |
|---|---|
| Blank page | Always open via http://127.0.0.1:5000, NOT by double-clicking the HTML file |
| Authentication error | Check your ANTHROPIC_API_KEY is set correctly |
| ModuleNotFoundError | Run `pip install -r requirements.txt` |
| Port already in use | Change `app.run(debug=True)` to `app.run(debug=True, port=5001)` |
