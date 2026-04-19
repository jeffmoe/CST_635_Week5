# CST_635_Week5 - Pandas vs PandasAI Data Filtering

## Project Overview

This project compares basic data filtering tasks between **Pandas** and **PandasAI** using a customer bank churn dataset from Kaggle. The goal is to evaluate the effectiveness and simplicity of AI-assisted data querying versus traditional Pandas filtering methods.

### Key Comparisons
- Filtering by **one column**
- Filtering by **two columns**
- Filtering by **three columns**

## Dataset

**Source:** [Customer Churn Modelling Dataset](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling/data) (Kaggle)

## Environment

| Component | Version / Specification |
|-----------|--------------------------|
| Python | 3.10.0 |
| PandasAI | 3.0.0 |
| OS | WSL2 Debian instance |
| LLM | Local instance (LM Studio) running on native Windows (GPU) |
| Virtual Environment | Used to avoid dependency conflicts |

> **GitHub Repository:** [https://github.com/jeffmoe/CST_635_Week5.git](https://github.com/jeffmoe/CST_635_Week5.git)

## LLM Local Setup (LM Studio)

### Steps to Configure LM Studio
1. Go to the **Developer** tab
2. Click the **gear icon** (top left) for server settings
3. Ensure:
   - **Require authentication** is OFF
   - **Serve on local network** is ON
4. Toggle the **server on** (top left)
5. **Load a model** (e.g., `gemma-4-e4b`)
6. Copy the **URL** provided by LM Studio (used for PandasAI setup)

## PandasAI Integration

### Installation
```bash
pip install pandasai pandasai-litellm
