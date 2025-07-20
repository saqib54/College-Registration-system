<!-- Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:007BFF,100:28a745&height=200&section=header&text=College%20Registration%20System%20(C%2B%2B)&fontSize=40&fontColor=ffffff" alt="College Registration System"/>

<h2 align="center">🎓 College Registration System — C++ Project</h2>

<p align="center">
  A console-based system that allows student registration,<br>
  handles in-state and out-of-state enrollment, and generates reports.<br>
  Data is saved to a file for persistence.
</p>

---

### 🛠 Features

- ✅ Register students into the system  
- ✅ Detect and manage **In-State** and **Out-of-State** students  
- ✅ Automatically calculate tuition or categorization (if implemented)  
- ✅ Generate detailed report of all registered students  
- ✅ Save student data to a file (e.g., `students.txt`)

---

### 💾 File Handling

✔ The project uses **file I/O** (`fstream`) to store student records.  
✔ When a student registers, their data is saved to a file (e.g., `students.txt` or `record.txt`).  
✔ This allows the application to keep data even after it closes.

---

### 📂 Project Structure

| File Name         | Description                          |
|------------------|--------------------------------------|
| `main.cpp`       | Main C++ file with all functionality |
| `students.txt`   | File that stores registered students |
| `README.md`      | This file (project documentation)    |

---

### 📸 Sample Console Output
--- College Registration System ---

Register Student

Show All Students

Generate Report

Exit

Enter choice: 1

Enter student name: Ali
Enter state (in/out): in
Student registered successfully!

Data saved to students.txt

yaml
Copy
Edit

---

### ⚙️ How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/saqib54/College-Registration-system.git
Open main.cpp in a C++ IDE (Code::Blocks, Dev C++, VS Code, etc.)

Compile & run:

bash
Copy
Edit
g++ main.cpp -o registration
./registration
🧾 Example Output in students.txt
markdown
Copy
Edit
Name: Ali
State: In-State
---------------------------
Name: John
State: Out-of-State
---------------------------
👨‍💻 Author
Saqib
🔗 GitHub: github.com/saqib54

🌟 Support & Contribution
If this project helped you, give it a ⭐ star!
Feel free to fork and improve the features (e.g., fee calculation, search filter, etc.)

<p align="center"> <img src="https://capsule-render.vercel.app/api?type=waving&color=0:28a745,100:007BFF&height=120&section=footer"/> </p> ```
