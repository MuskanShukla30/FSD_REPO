<h1 align="center">🐍 Python Fundamentals Practice</h1>

<p align="center">
  <strong>A small collection of beginner Python programs for practicing input, conditionals, loops, and functions.</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python 3" />
  <img src="https://img.shields.io/badge/Dependencies-Standard%20Library-brightgreen?style=flat-square" alt="No third-party dependencies" />
</p>

---

## ✨ Overview

`FSD_REPO` contains five short, independent Python scripts. Each one prompts for input or prints output in the terminal, providing small examples of common programming fundamentals.

## 📚 Exercises

| File | What it does | Concepts practiced |
|---|---|---|
| [`calculate_sqaure.py`](calculate_sqaure.py) | Reads an integer and prints its square. | Functions, integer input, exponentiation, formatted output |
| [`even_or_odd.py`](even_or_odd.py) | Reads an integer and reports whether it is even or odd. | Input, modulo, conditionals |
| [`password_check.py`](password_check.py) | Repeatedly prompts until the entered text matches the expected practice password. | `while` loops, strings, conditionals |
| [`print_numbers.py`](print_numbers.py) | Prints the integers 1 through 10. | `for` loops and `range()` |
| [`temperature_check.py`](temperature_check.py) | Reads a temperature and classifies it as Cold, Warm, or Hot. | Numeric input, comparisons, `if`/`elif`/`else` |

## 🧰 Requirements

- Python 3
- No third-party packages

## 🚀 Run the scripts

Clone the repository and open a terminal in its directory:

```bash
git clone https://github.com/MuskanShukla30/FSD_REPO.git
cd FSD_REPO
```

Run any exercise with Python. For example:

```bash
python even_or_odd.py
```

On some systems, use `python3` instead of `python`:

```bash
python3 temperature_check.py
```

Other scripts can be run the same way, using their filenames. Follow the prompts in the terminal where applicable.

## 🧭 Temperature Categories

`temperature_check.py` uses these thresholds:

| Input temperature | Output |
|---:|---|
| Below 15 | Cold |
| 15 through 25, inclusive | Warm |
| Above 25 | Hot |

## 🔐 Password Exercise Note

`password_check.py` compares the entered value with the hard-coded practice string `python123`. This illustrates a loop and string comparison only; hard-coded passwords are not suitable for real authentication.

## 📁 Repository Structure

```text
FSD_REPO/
├── calculate_sqaure.py      # Calculate a number's square
├── even_or_odd.py           # Check integer parity
├── password_check.py        # Repeat prompt until correct practice password
├── print_numbers.py         # Print numbers 1–10
├── temperature_check.py     # Classify an entered temperature
└── README.md
```

---

<p align="center"><strong>Small programs, one concept at a time 🐍</strong></p>
