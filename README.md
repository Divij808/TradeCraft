# TradeCraft
It is a secure local web application which allows users to track live stocks, manage their accounts, and obtain real-time financial news.


---

## ⚡ Features
- 📈 Live stock prices: Retrieving real-time financial data through the use of a centralised price service.
- 📰 Integrated RSS feeds providing access to the latest market news.
- 🔐 Secure user verification: Before allowing login, the sign-up system carries out email-based OTP (One-Time Password) verification.
- 🛡️ **Strong validation:** The system will properly deal with invalid stock symbols and inputs without crashing.
- 💾 Local persistence: The system automatically creates an SQLite database and manages the database schema without any additional setup.

---

## 🔀 2 Setup options

### Option A: Running from Source Code (For Developers)

1. **Prerequisites**
   Ensure you have the following installed:
   - Python 3.9 or a later version
   - `pip` (Python package manager)
   - A code editor like PyCharm
   - Active internet connection

   *To check your Python version:*
   ```bash
   python --version

```

2. **Download & Open**
Get the project ZIP file and extract it into a folder.
Go ahead and open the folder in your code editor.


3. **Install Dependencies**
Go to the install folder and run install.py:
* **Flask** → Web framework
* **yfinance** → Live stock prices
* **feedparser** → News feeds
* **requests** → API requests




4. **Run the Application**
* In your project root directory, run:
```bash
python app.py

```


Open the browser and navigate to: `http://127.0.0.1:5000`



---

### Option B: Running the standalone app (".exe" release) (for users)

1. **Download the app**
Go to the **Releases** section of this repository.
Get the latest app.zip file.


2. **📂 Extract the files**
Click the right mouse button on app.zip and then select Extract All....


3. **Launch the application**
Open the folder that has been extracted and double-click on **app.exe**. *(Make sure that the terminal window remains open when you're using the app!)*


4. **🌐 Access through your browser**
Open the browser and go to: http://127.0.0.1:5000


5. **🛑 Shutting Down**
To safely stop the local server, close the terminal window.



---

## 🛠️ Troubleshooting

* **Problem: Module not found**
* *Fix:* Run your `pip install` commands again or check your virtual environment.


* **Problem: Live price not loading**
Solution: Make sure your internet connection is working and confirm that the stock ticker symbol is correct.


* **Problem: Page not loading**
Solution: Make sure that the Flask server is actually running in your terminal and that you are using the right local URL.



---

## Credits & Acknowledgements

The program was developed using Flask, yfinance, and feedparser. A special thank-you goes to the open-source contributors and the providers of financial data.

```

```
