## Fortnite QA Automation  

Automated testing framework for Fortnite game mechanics and UI validation. This repository contains test scripts for game functionality, network stability, and API interactions.

### Features  
- Automated UI testing with Selenium WebDriver  
- API interaction and validation using REST Assured  
- Performance monitoring through in-game telemetry analysis  
- CI/CD pipeline for test execution with GitHub Actions  

### Technologies  
- **Python 3.9+**  
- **Selenium WebDriver**  
- **pytest**  
- **REST Assured (API Testing)**  
- **Docker (optional for headless execution)**  

### Folder Structure  
```
/fortnite-qa-automation
    ├── tests/             # Automated test scripts
    ├── configs/           # Test environment configurations
    ├── reports/           # Test execution reports
    ├── logs/              # Execution logs for debugging
    ├── requirements.txt   # Dependencies
    ├── README.md          # Documentation
```

### Setup & Execution  
1. Clone the repository  
   ```bash  
   git clone https://github.com/thomas-sdet-qa-test/fortnite-qa-automation.git  
   ```  
2. Install dependencies  
   ```bash  
   pip install -r requirements.txt  
   ```  
3. Run UI tests  
   ```bash  
   pytest tests/ui_tests/  
   ```  
4. Run API tests  
   ```bash  
   pytest tests/api_tests/  
   ```  

### Notes  
- Ensure ChromeDriver is installed for Selenium tests.  
- API tests require valid authentication tokens.  

### Contribution  
Pull requests are welcome.
