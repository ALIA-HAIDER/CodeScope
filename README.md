# CodeScope


# 🚀 CodePulse

**Real-Time AI Code Maintainability Analyzer**

CodePulse is an AI-powered developer tool that analyzes source code and provides **real-time insights into maintainability, complexity, and code quality**. It helps developers identify potential issues early and write cleaner, more maintainable code.

The system extracts code metrics, evaluates maintainability scores, and provides AI-powered suggestions to improve code structure and readability.

---

## ✨ Features

* 📊 **Maintainability Score Prediction**
* 🧠 **Machine Learning Model for Code Quality**
* ⚡ **Real-Time Code Analysis**
* 📈 **Code Complexity Metrics**
* 🧩 **AST-based Feature Extraction**
* 💡 **AI Suggestions for Code Improvements**
* 🖥 **Interactive Dashboard**

---

## 🧠 How It Works

The system evaluates code quality through multiple stages.

```
User Code
   ↓
Code Parser (AST)
   ↓
Feature Extraction
   ↓
Machine Learning Model
   ↓
Maintainability Score
   ↓
AI Suggestions + Metrics Dashboard
```

---

## 📊 Metrics Analyzed

The model evaluates multiple code quality metrics including:

* Lines of Code (LOC)
* Number of Functions
* Cyclomatic Complexity
* Nesting Depth
* Loop Count
* Variable Count
* Comment Density

These metrics are used to estimate the **Maintainability Index**.

---


## 🏗 System Architecture

```
Frontend (React)
        │
        │ Code Input
        ▼
Backend API (Node.js)
        │
        │ Extract Code Metrics
        ▼
ML Model API (FastAPI)
        │
        │ Predict Maintainability
        ▼
Dashboard Visualization
```

---


---

## 🧪 Model Training

The maintainability model is trained using extracted code metrics from open-source repositories.

Training pipeline:

```
Dataset Collection
     ↓
Feature Extraction
     ↓
Model Training
     ↓
Model Serialization (.pkl)
```


