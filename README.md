<h1 align="center">🔐 Password Generator</h1>

<p align="center">
  A simple and professional command-line password generator built with Python.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge" alt="No dependencies">
  <img src="https://img.shields.io/badge/Security-secrets%20module-blue?style=for-the-badge" alt="secrets module">
</p>

---

## 📌 About

Weak passwords are easy to guess. This tool generates strong, random passwords based on your choice of character types and length, and tells you how strong the generated password is.

## ✨ Features

- 🔢 Numbers only passwords
- 🔤 Alphabets only passwords
- 🔤🔢 Alphanumeric passwords
- 🔐 Alphanumeric + symbols passwords
- 📏 Custom password length
- 💪 Password strength check
- 🔄 Generate multiple passwords at once
- ❌ Invalid input handling (no crash on wrong input)
- 🔒 Uses Python's `secrets` module, which is designed for secure random values

## 🛠️ Tech Used

- Python 3.x
- Built-in modules only (no installation needed)

## 🚀 How to Run

1. Install [Python](https://www.python.org/downloads/).
2. Clone this repository:

   ```bash
   git clone https://github.com/decodewithaayat/Python-Password-Generator-by-MinzaIX.git
   cd Python-Password-Generator-by-MinzaIX
   ```

3. Open PowerShell or Command Prompt in the project folder and run:

   ```bash
   python Password_Generator.py
   ```

4. Choose the password type, enter the length, and get your password.

## 🔒 Security Note

This project uses the `secrets` module instead of `random`. The `random` module is not meant for security purposes, while `secrets` generates cryptographically strong random values suitable for passwords.

## 💡 Tips for a Strong Password

- Use **12 or more characters**
- Mix uppercase, lowercase, numbers and symbols
- Use a different password for every account
- Store passwords in a trusted password manager

## 🔮 Future Improvements

- [ ] Copy password to clipboard
- [ ] Save passwords to an encrypted file
- [ ] GUI version
- [ ] Exclude similar-looking characters (`O`, `0`, `l`, `1`)

## 👨‍💻 Author

**Shaikh Aayat Ullah** (MinzaiX)

[GitHub](https://github.com/decodewithaayat) • [LinkedIn](https://www.linkedin.com/in/shaikh-aayat-a34797392)


![Screenshot](screenshot.png)
