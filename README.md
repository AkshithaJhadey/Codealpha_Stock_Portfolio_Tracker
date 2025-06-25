
# 📊 Stock Portfolio Tracker

## 🧾 Project Description

A simple command-line application to help you track your stock investments. You can input stock names and quantities, calculate the total value of your portfolio based on predefined prices, and optionally save the result to a `.txt` or `.csv` file.

---

## ✅ Features

- Input stock symbols and quantities interactively.
- Predefined stock price dictionary for calculations.
- Calculates total investment value.
- Option to export data to `.txt` or `.csv`.

---

## 🛠️ Technologies Used

- Python 3
- Key Concepts:
  - `dictionary`
  - `input/output`
  - `basic arithmetic`
  - `file handling` (optional)

---

## 🚀 How to Run

1. Make sure Python 3 is installed.
2. Save the code in a file named `stock_tracker.py`.
3. Run the file in your terminal or command prompt:
   ```bash
   python stock_tracker.py
   ```
4. Follow the prompts to:
   - Enter stock symbols (e.g., AAPL, TSLA, MSFT)
   - Enter quantities
   - View your total investment
   - Optionally save the output to a `.txt` or `.csv` file

---

## 💡 Example Usage

```text
Available stocks: AAPL, TSLA, GOOGL, MSFT, AMZN

Enter stock symbol (or 'done' to finish): AAPL
Enter quantity for AAPL: 5
Enter stock symbol (or 'done' to finish): TSLA
Enter quantity for TSLA: 2
Enter stock symbol (or 'done' to finish): done

Investment Summary:
AAPL: 5 x $180 = $900
TSLA: 2 x $250 = $500

Total Investment Value: $1400

Do you want to save this to a file? (yes/no): yes
Enter filename (with .txt or .csv): portfolio.csv
Data saved to portfolio.csv
```

---

## 📂 File Structure

```
stock_tracker.py
README.md
portfolio.csv (if saved)
```

---

## 📬 Contributing

Pull requests are welcome! Feel free to fork the repo and submit suggestions or improvements.

---

## 📄 License

This project is open-source and free to use.
