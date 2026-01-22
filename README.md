# ASCII Art Project

A simple **Python console application** that generates large ASCII art representations of characters, words, numbers, and ranges using a predefined ASCII font.

---

## 📌 Features

* Display ASCII art for:

  * A **single character**
  * **Words** (alphanumeric, up to 15 characters)
  * **Alphabet ranges** (e.g., `A-D`)
  * **Only alphabets**
  * **Only numbers**
* Interactive **menu-driven UI**
* Supports:

  * Alphabets (A–Z)
  * Numbers (0–9)
  * Special characters: space, `@`, `_`, `-`, `.`

---

## 🛠 Requirements

* Python **3.x**
* Windows OS (uses `msvcrt` and `cls` command)

> ⚠️ This project is **Windows-only** due to the use of the `msvcrt` module.

---

## ▶️ How to Run

1. Clone or download the project
2. Open a terminal or command prompt
3. Navigate to the project directory
4. Run the program:

```bash
python asciiartproject.py
```

---

## 📋 Menu Options

1. **One Character** – Display ASCII art for a single character
2. **Words** – Display ASCII art for alphanumeric strings (max 15 characters)
3. **Range** – Display ASCII art for alphabet ranges (e.g., `A-F`)
4. **Only Alphabets** – Accepts alphabet-only input
5. **Only Numbers** – Accepts numeric-only input
6. **Exit** – Quit the program

---

## 🧠 How It Works

* ASCII patterns are stored in a list (`data`)
* Each character occupies **6 columns** in the ASCII font
* Character positions are calculated using ASCII values (`ord()`)
* The program prints character slices line-by-line to form large text

---

## 📷 Example Output

```
 *****  ***   ***  
   *   *   * *   *
   *   *   * *   *
   *   *   * *   *
   *    ***   ***
```

---

## 🚀 Future Improvements

* Cross-platform support (Linux / macOS)
* Custom font styles
* Save ASCII output to a file
* Colorized ASCII art

---

## 👨‍💻 Author

[Jayantilal Baghrecha]
