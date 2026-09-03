Here is your newly polished, highly scannable `README.md` file layout. It merges your TradeCraft installation options with the professional structure that reviewers and judges love to see!

```markdown
# TradeCraft
A secure local web application for tracking live stocks, managing user accounts, and fetching real-time financial news.


---

## ⚡ Features
- 📈 **Live Stock Prices:** Real-time financial data fetching using a centralised price service.
- 📰 **Stock News Feeds:** Integrated RSS feeds for up-to-date market news.
- 🔐 **Secure User Verification:** Sign-up system with email-based OTP (One-Time Password) verification before login.
- 🛡️ **Robust Validation:** Safe handling of invalid stock symbols and inputs without crashing.
- 💾 **Local Persistence:** Automated SQLite database creation and schema management out-of-the-box.

---

## 🔀 Choose Your Setup Method

### Option A: Running from Source Code (For Developers)

1. **Prerequisites**
   Ensure you have the following installed:
   - Python 3.9 or later
   - `pip` (Python package manager)
   - A code editor like PyCharm
   - Active internet connection

   *To check your Python version:*
   ```bash
   python --version

```

2. **Download & Open**
* Download the project ZIP and extract it to a folder.
* Open that folder inside your code editor.


3. **Install Dependencies**
* Navigate to the `install` folder and run `install.py`:
* **Flask** → Web framework
* **yfinance** → Live stock prices
* **feedparser** → News feeds
* **requests** → API requests




4. **Run the Application**
* In your project root directory, run:
```bash
python app.py

```


* Open your browser and go to: `http://127.0.0.1:5000`



---

### Option B: Running the Standalone App (.exe Release) (For Users)

1. **📥 Download the App**
* Head over to the **Releases** section of this repository.
* Download the latest `app.zip` file.


2. **📂 Extract the Files**
* Right-click `app.zip` and choose **Extract All...**


3. **💻 Launch the Application**
* Open the extracted folder and double-click **`app.exe`**. *(Keep the terminal window open while using the app!)*


4. **🌐 Access in Your Browser**
* Open your browser and navigate to: `http://127.0.0.1:5000`


5. **🛑 Shutting Down**
* Close the terminal window or press `Ctrl + C` inside it to safely stop the local server.



---

## 🛠️ Troubleshooting

* **Problem: Module not found**
* *Fix:* Re-run your `pip install` commands or check your virtual environment.


* **Problem: Live price not loading**
* *Fix:* Check your internet connection and verify that the stock ticker symbol is correct.


* **Problem: Page not loading**
* *Fix:* Ensure the Flask server is actively running in your terminal and you are using the correct local URL.



---

## 🙏 Credits & Acknowledgements

Built using Flask, yfinance, and feedparser. Special thanks to open-source contributors and financial data providers.

```

```
