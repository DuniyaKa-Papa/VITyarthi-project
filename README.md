
# 🎓 VIT-Yarthi Student Grade Management System

A powerful **GUI-based Student Marks Management System** built using **Python & Tkinter**. This application helps manage student records efficiently with modern features like **data visualization, PDF/CSV export, auto-repair system, and dark/light mode**.

---

## 👤 Author
**Anadi Rathore**

---

## 🚀 Features

- ✅ Add, Update & Delete student records  
- ✅ Automatic Grade Calculation (S, A, B, C, D, E, N)  
- ✅ Live Search & Sorting (by Roll, Name, Marks)  
- ✅ Bar Chart & Line Chart Visualization  
- ✅ Export Student Data to **CSV**  
- ✅ Generate Detailed **PDF Reports**  
- ✅ **Auto-Repair System** for corrupted JSON files  
- ✅ **Dark / Light Mode Toggle**  
- ✅ Class Statistics (Highest, Lowest, Average)  

---

## 🛠 Technologies Used

- **Python 3**
- **Tkinter** – GUI
- **Matplotlib** – Charts & Visualization
- **ReportLab** – PDF Generation
- **Pillow (PIL)** – Image Handling
- **JSON & CSV** – Data Storage

---

## 📂 Project Structure

```
VIT-Yarthi/
│
├── main.py            # Main Application File
├── students.json      # Student Data File (auto-created)
├── logo.png           # App Logo (optional)
└── README.md          # Project Documentation
```

---

## ⚙️ Installation

### 1️⃣ Install Required Libraries
```
pip install matplotlib reportlab pillow
```

### 2️⃣ Run the Program
```
python main.py
```

---

## 📊 Grading System

| Marks Range | Grade |
|-------------|--------|
| 90 – 100    | S      |
| 80 – 89     | A      |
| 70 – 79     | B      |
| 60 – 69     | C      |
| 50 – 59     | D      |
| 40 – 49     | E      |
| Below 40    | N (Fail) |

---

## 📄 PDF Report Includes

- Institute Title
- Logo (if available)
- Student Ranking
- Marks & Grades
- Summary Statistics
- Visual Charts

---

## 🛡 Auto-Repair Feature

If the `students.json` file becomes corrupted or is in old format, the system:
- Repairs the data automatically  
- Converts old formats  
- Saves a clean working file instantly  

---

## 📌 Highlights

- Fully Offline Application  
- Clean & Modern UI  
- Accurate Data Handling  
- Student Performance Analytics  
- Real-time Updates  

---

## 📜 License

This project is created for **educational and academic use**.

---

🏴‍☠️**THE END**
