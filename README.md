## Epic Games Data Pipeline  

Data analytics and machine learning pipeline for player behavior analysis in Epic Games. This project processes player statistics, game telemetry, and in-game events to generate predictive insights.

### Features  
- Real-time data ingestion and preprocessing  
- Machine learning models for player behavior prediction  
- Game telemetry processing with Apache Spark  
- Interactive data visualization with Jupyter Notebooks  

### Technologies  
- **Python 3.9+**  
- **Pandas, NumPy**  
- **Scikit-Learn**  
- **Apache Spark**  
- **Jupyter Notebooks**  

### Folder Structure  
```
/epicgames-data-pipeline
    ├── data/            # Raw and processed datasets
    ├── models/          # Trained ML models
    ├── notebooks/       # Jupyter Notebooks for analysis
    ├── scripts/         # Data preprocessing and ML scripts
    ├── README.md        # Documentation
```

### Setup & Execution  
1. Clone the repository  
   ```bash  
   git clone https://github.com/thomas-sdet-qa-test/epicgames-data-pipeline.git  
   ```  
2. Install dependencies  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run data preprocessing  
   ```bash  
   python scripts/data_preprocessing.py  
   ```  

### Contribution  
Pull requests are welcome.
