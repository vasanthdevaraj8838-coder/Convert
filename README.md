# 📄 JSON to CSV Converter (Python)

A lightweight Python script that converts structured JSON data into CSV format. The program reads an `input.json` file, extracts key fields, and generates a clean, comma-separated `output.csv` file. This tool is useful for converting JSON datasets into spreadsheet-friendly formats for analysis or reporting.

---

## 🚀 Features

- Reads JSON data from `input.json`
- Automatically extracts fields: **Name**, **age**, and **birthyear**
- Writes the converted data into `output.csv`
- Handles errors gracefully with exception reporting
- Simple and beginner-friendly code structure

---

## 🧠 How It Works

1. The script loads JSON content from `input.json`
2. It reads the header keys from the first JSON object
3. Iterates through every JSON entry and formats values as CSV rows
4. Saves all rows into the `output.csv` file
5. Prints an error message if file or parsing issues occur

---

## 🛠️ Technologies Used

- **Python**
- **JSON Module**
- **File I/O**
- **CSV Formatting**
- **Exception Handling**
