<img width="1600" height="752" alt="image" src="https://github.com/user-attachments/assets/662964f1-cae5-43c2-b36f-851dd34765f9" />
This project can be automated through GitHub Releases


# What is TradeCraft❓
TradeCraft is a web app that allows you to simulate a stock exchange with ease through an intuitive graphical interface and Virtual money. It automates the process of sourcing, calculating, abstracting, and visually presenting transaction statistics like a real stock exchange would.

TradeCraft relies heavily on Yahoo Finance to source its data. This project would not be possible without their contributions.

This project also serves as my coursework for the OCR A Level Computer Science NEA. Feel free to clone and experiment with the EAS for your own learning.

## ⚡ Features
- 📈 **Live Stock Prices:** Real-time financial data fetching using a centralised price service.
- 📰 **Stock News Feeds:** Integrated RSS feeds for up-to-date market news.
- 🔐 **Secure User Verification:** Sign-up system with email-based OTP (One-Time Password) verification before login.
- 🛡️ **Robust Validation:** Safe handling of invalid stock symbols and inputs without crashing.
- 💾 **Local Persistence:** Automated SQLite database creation and schema management out-of-the-box.

# 📋Requirements
For now, TradeCraft will also be available on the GitHub release page as an exe file.

TradeCraft isn’t designed for small screens (e.g. phones). Please use a larger device(e.g., a laptop) for the best experience.

To run TradeCraft, you will need:

Python 3.x with pip
A Yahoo Finance API token (although a cached database has been included)
Dependencies will be installed during the setup process.
An IDE that can run Python

# ⚙️ Installation and Launch
1. **Download & Open**
   - Download the provided TradeCraft ZIP file and extract it to a folder on your computer.
   - Open that folder in your code editor.

2. ** Install Required Python Packages**
   - Open the folder called `install` and run `install.py` to install Flask, yfinance, feedparser, and requests.

3. **Database Setup**
   - No manual SQLite setup is required; on the first run, the database file (`tradecraft.db`) and its tables are automatically created.

4. **Running the Application**
   - In the project root directory, run:
     ```bash
     python app.py
     ```
   - Open your web browser and go to `http://127.0.0.1:5000`.
     

# 📦 Dependencies
   The backend uses the following libraries:
      
      - Flask
      - requests
      - Companies.json (More to be added as the project develops.)
      - App.js (More to be added as the project develops.)
      
## 🛠️ Troubleshooting

- **Problem: Module not found**
  - *Fix:* Re-run your `pip install` commands or check your virtual environment.

- **Problem: Live price not loading**
  - *Fix:* Check your internet connection and verify that the stock ticker symbol is correct.

- **Problem: Page not loading**
  - *Fix:* Ensure the Flask server is actively running in your terminal and you are using the correct local URL.
    <br>
# ⚖️ License
This repository uses the Creative Commons Attribution-NoDerivatives 4.0 International (CC BY-ND 4.0) license.

# Author
Divij Mekala – @Divij808
