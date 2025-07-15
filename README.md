# 🥒 Data Pickle Pipe

A simple Python pipeline that demonstrates how to **serialize and deserialize** data using the built-in `pickle` module. This project highlights how pickling can be used to efficiently store intermediate data in machine learning or ETL workflows.

## 🎯 Purpose

- Save intermediate or final Python objects (e.g., DataFrames, models)
- Load pickled data for future reuse or continuation
- Simple, reusable interface for pipeline stages involving pickling

## 📁 Project Structure

```text
data-pickle-pipe/
├── src/
│   ├── pickle_io.py        # Contains functions for pickling/unpickling data
│   └── main.py             # Sample pipeline that uses pickling
├── data/
│   └── raw_data.csv        # Sample raw input (optional)
├── outputs/
│   ├── processed.pkl       # Pickled object
│   └── restored.csv        # Unpickled and saved data
├── notebooks/
│   └── demo.ipynb          # Interactive walkthrough
├── requirements.txt
└── README.md
```
## ✅ Use Cases
Save ML models between training and inference

Cache transformed data to speed up workflows

Backup Python objects in pipelines or applications

## 📌 TODO
Add JSON and joblib serialization support

CLI support for batch pickling

Integrate with pandas pipeline stages

## 👤 Author
Saran Jaya Thilak
