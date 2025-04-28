# Helenium E2E Testing with Behave

This project explores **Helenium’s AI-powered self-healing** in **BDD-style end-to-end (E2E) tests** using **Behave**.  
It compares **traditional Selenium** automation against **Helenium** to improve test stability, reduce maintenance, and handle dynamic UI changes gracefully.

---

## 🚀 Project Goals
- Evaluate **self-healing** automation using **Helenium** with real-world UI changes.
- Benchmark differences between **pure Selenium** and **Selenium + Helenium**.
- Integrate with **Allure** for beautiful, real-time test reporting.
- Make tests easy to read, write, and maintain using **BDD best practices**.

---

## 🛠️ Tech Stack
- **Python 3.x**
- **Behave (BDD Framework)**
- **Selenium WebDriver**
- **Helenium**
- **Allure Behave Adapter**
- **GitHub Actions / Jenkins** (for CI/CD)

---

## 📊 Key Features
✅ **Self-Healing UI Automation** with Helenium  
✅ **Readable BDD Scenarios** with Gherkin syntax (`.feature` files)  
✅ **Traditional vs. AI-Powered Testing** comparison  
✅ **Allure Reporting** integration for real-time feedback  
✅ **CI/CD Friendly** setup for automated pipelines  

---

## 🏗️ Project Structure
```bash
📂 helenium_behave_project  
 ├── 📂 features/  
 │    ├── 📂 steps/        # Step definitions  
 │    ├── 📂 pages/        # Page Object Models (POMs)  
 │    ├── 📂 environment/  # Hooks and setup/teardown  
 │    ├── *.feature        # Gherkin feature files  
 ├── requirements.txt     # Python dependencies  
 ├── behave.ini           # Behave configuration  
 ├── README.md            # This file  
```
---
##🚦 How to Run
1️⃣ Clone the Repo
```bash
git clone https://github.com/your-username/your-helenium-behave-project.git
cd your-helenium-behave-project
```
2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
3️⃣ Run Tests with Behave
```bash
behave --tags=@yourtag --no-capture --alluredir=allure-results
```
(Or just behave to run all tests.)

4️⃣ Generate and View Allure Report
```bash
allure serve allure-results
```
