# 🎭 Playwright Python Automation Framework

A Python-based web automation testing framework built using **Playwright and Pytest**. This project focuses on browser automation, web application testing, reusable test components, and structured test execution.

## 🚀 Tech Stack

- **Python** – Programming language
- **Playwright** – Browser automation
- **Pytest** – Test framework
- **Page Object Model (POM)** – Test organization
- **pytest-html** – HTML test reporting

## 📁 Project Structure

```text
PlaywrightPython/
│
├── assets/              # Supporting project assets
├── pages/               # Page Object Model classes
├── reports/             # Test execution reports
├── test_data/           # Test data files
├── tests/               # Automated test cases
│
├── pytest.ini           # Pytest configuration
├── requirements.txt     # Project dependencies
├── conftest_old.py      # Previous Pytest fixtures
└── report1.html         # HTML test report
```

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/Shashi-Srivastav/PlaywrightPython.git
```

### 2. Navigate to the project

```bash
cd PlaywrightPython
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

Activate it:

**Windows**
```bash
venv\Scripts\activate
```

**macOS / Linux**
```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Install Playwright browsers

```bash
playwright install
```

## ▶️ Running Tests

Run all tests:

```bash
pytest
```

Run a specific test file:

```bash
pytest tests/test_example.py
```

Run tests in verbose mode:

```bash
pytest -v
```

Show print statements and detailed output:

```bash
pytest -v -s
```

## 📊 HTML Test Reports

Generate an HTML report using pytest-html:

```bash
pytest --html=reports/report.html --self-contained-html
```

The generated report provides an overview of test execution results.

## 🎯 Project Objectives

- Automate browser interactions using Playwright.
- Understand Pytest test discovery and execution.
- Implement reusable automation methods.
- Practice web element identification and interaction.
- Organize automation scripts.
- Generate and analyze test execution reports.

## 📚 Learning Outcomes

This project demonstrates practical experience with:

- Python fundamentals
- Playwright browser automation
- Pytest framework
- Locators and assertions
- Browser and page handling
- Fixtures and setup/teardown
- Page Object Model concepts
- Test execution and reporting

## 👨‍💻 Author

**Shashi Srivastava**

- GitHub: [Shashi-Srivastav](https://github.com/Shashi-Srivastav)
- Portfolio: [shashi-srivastav.vercel.app](https://shashi-srivastava.vercel.app/)

---

⭐ If you find this project useful, consider giving it a star!
