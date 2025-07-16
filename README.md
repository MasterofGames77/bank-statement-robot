# 🏦 UiPath Automated Bank Reconciliation Process

This UiPath automation project performs **bank statement reconciliation** by comparing transaction records from an internal ledger with a bank-provided statement. The bot flags discrepancies and outputs a formatted Excel report summarizing the results.

---

## 📂 Project Structure

├── Main.xaml # Main workflow sequence
├── project.json # UiPath project metadata
├── Input/ # Folder for input Excel files
├── Output/ # Folder for generated reconciliation report
└── .gitignore # Ignore temp, log, and environment-specific files

---

## 🚀 Features

- 🔍 **Data Comparison**: Compares transactions between two Excel sources (bank vs. internal)
- 🧠 **Transaction Matching**: Uses nested loops to identify matched, unmatched, and extra transactions
- 📊 **Excel Report**: Generates a user-friendly report with basic formatting
- 🛠️ **UiPath Best Practices**: Clean structure and reusable logic blocks

---

## 📥 How to Use

1. Place your Excel input files in the `Input/` folder
2. Open the solution in **UiPath Studio**
3. Run the automation
4. Check the `Output/` folder for the reconciliation report

---

## 🔧 Requirements

- UiPath Studio 2022.10+ (Community or Enterprise)
- Excel installed on the machine (for workbook activities)

---

## 📌 Notes

- Make sure column headers in the input files match the expected names (e.g., `Transaction ID`)
- You can adjust the sheet names, file paths, and data schemas in `Main.xaml` as needed

---

## 📄 License

This project is open-source under the [MIT License](LICENSE)
