# Airlines On-time Performance Data Consolidation

## 📌 Project Overview
This project features a Python script, `concat_and_upload_airlines_data.py`, designed to streamline the preprocessing of Airlines On-time Performance data. The script concatenates multiple monthly dataset files into a unified DataFrame using pandas and uploads the resulting dataset to a **PostgreSQL database** via SQLAlchemy for subsequent analysis. This automation enhances efficiency in handling large-scale flight data, making it ready for SQL-based insights.
## 📂 Dataset
- **Source:** [ U.S. Department of Transportation's On-Time Performance Data](https://transtats.bts.gov/Tables.asp?QO_VQ=EFD&QO_anzr=Nv4yv0r%FDb0-gvzr%FDcr4s14zn0pr%FDQn6n&QO_fu146_anzr=b0-gvzr)
## Features
- Concatenates monthly CSV files into a single dataset.
- Handles large datasets efficiently with pandas.
- Uploads the unified dataset to PostgreSQL using SQLAlchemy.
- Prepares data for downstream analysis 
## 🛠️ Technologies used
- **Programming Language:** Python.
- **Libraries:** Before running the script, ensure you have the following installed:
- Python 3.8+
- pandas (`pip install pandas`)
- SQLAlchemy (`pip install sqlalchemy`)
- psycopg2 (`pip install psycopg2-binary`) for PostgreSQL connectivity
- PostgreSQL server running locally or remotely
- Airlines On-time Performance dataset files (e.g., CSV format) from a reliable source
  
## 🔧 Installation & Setup

### **Step 1: Clone the Repository**
```
git clone https://github.com/anieze-gad/concat_and_upload_airlines_data.py
```

### **Step 2: Install Dependencies**
```
pip install -r requirements.txt
```

### **Step 3: Open the Jupyter Notebook**
```
jupyter notebook
```
Open On-time Performance Data consolidation for SQL analysis.ipynb to explore the analysis and forecasting results.

# Contributing
Feel free to fork this repository, submit pull requests, or suggest improvements via issues. Contributions to enhance functionality (e.g., error handling, additional file formats) are welcome!

# 👨‍💻 Author
### **Anieze Ifesinachi Gad**
📧 Email: aniezegad7@gmail.com 
🔗 GitHub: [anieze-gad](https://github.com/anieze-gad)

# 📜 License
This project is licensed under the MIT License.


