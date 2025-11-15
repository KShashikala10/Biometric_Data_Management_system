
# 🧬 Biometric Data Management System  

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python&logoColor=white)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![License](https://img.shields.io/badge/License-Open--Source-orange)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20Mac-lightgrey)
![File Handling](https://img.shields.io/badge/File%20Handling-Optional-9cf)
![Contributions](https://img.shields.io/badge/Contributions-Welcome-blueviolet)

---

A Python-based application to manage biometric records including ID, name, age, DOB, nationality, biometric type, and visa number.  
Supports full CRUD functionality with optional file handling for persistent storage.

---

## 🚀 Features

### 🔹 Core Functions  
- **Create Biometric Data**  
- **Delete Biometric Data**  
- **Update Biometric Data**  
- **Verify Biometric Data**  
- **Display All Records**  
- **Manage Enrollment Data**

### 🔹 Optional File Handling  
- **Persistent Storage** using `biometric_data.txt`  
- **Save & Load** operations after every modification  

---

## 💾 File Handling Options

### ✅ With File Handling  
Data remains saved across program runs.

### ❌ Without File Handling  
Data is stored in memory only (temporary).

---

## ⚙️ Setup Instructions

### With File Handling
```bash
python main.py
````

### Without File Handling

Comment out:

* `self.load_data_from_file()`
* `self.save_data_to_file()`

---

## ▶️ How to Use

| Option | Description           |
| ------ | --------------------- |
| 1      | Create biometric data |
| 2      | Delete biometric data |
| 3      | Update biometric data |
| 4      | Verify biometric data |
| 5      | Display all records   |
| 6      | Manage enroll data    |
| 7      | Exit                  |

---

## 📚 Example Behavior

### With File Handling

✔ Data persists
✔ Records saved to `.txt`

### Without File Handling

❌ Data cleared after exit

---

## 🛠 Technologies Used

![Python](https://img.shields.io/badge/Python-Programming-blue?logo=python)
![File I/O](https://img.shields.io/badge/File%20Handling-Txt%20Storage-yellow)
![CLI](https://img.shields.io/badge/Interface-CLI-lightgrey)

---

## 🤝 Contributing

Pull requests are welcome!

---

## 📄 License

Open-source — free to use and modify.

