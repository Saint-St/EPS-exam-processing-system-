```markdown
# 🎓 Examination Processing System

A Java program to process university examination data, generate report cards, and store records in a text-based database. Built for **BBT 1203 EC March 2025** semester project.

---

## 🚀 Features
- 📁 **Store student data** in `students_database.txt`
- 📊 **Calculate grades** using Strathmore University's grading system
- 📄 **Generate report cards** with:
  - Student name & ID
  - Subject scores
  - Average score & grade
  - Recommendation (e.g., "Excellent", "Good")
  - Report generation date
- 🛠️ **Modular design** with separate methods for input, processing, and output

---

## 📦 Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/exam-processing-system.git
   ```
2. **Ensure Java 8+** is installed:
   ```bash
   java -version
   ```
   ⚠️ If not installed, download from [Oracle Java](https://www.oracle.com/java/technologies/downloads/)

---

## 🖥️ Usage
1. **Compile the program**:
   ```bash
   javac Student.java ExamProcessingSystem.java
   ```
2. **Run the program**:
   ```bash
   java ExamProcessingSystem
   ```
3. **Follow prompts** to:
   - Enter 10 student names/IDs
   - Input scores for 5 subjects (Math, English, Science, History, Geography)
4. **View output**:
   - On-screen report cards
   - Persistent data in `students_database.txt`

---

## 📂 File Structure
```
📁 exam-processing-system/
├── 📄 Student.java           # Student class with grade calculations
├── 📄 ExamProcessingSystem.java  # Main program logic
└── 📄 students_database.txt  # Auto-generated database (created after first run)
```

---

## 🛠️ Development
### 🔄 Data Format (students_database.txt)
```
Name,ID,Math,English,Science,History,Geography,Average,Grade,Recommendation,Date
John Doe,S123,85.0,78.0,92.0,88.0,75.0,83.6,A,Excellent,10/04/2025
```

### 🌟 Grading System
| Average Score | Grade | Recommendation |
|---------------|-------|----------------|
| ≥ 70          | A     | Excellent      |
| ≥ 60          | B     | Good           |
| ≥ 50          | C     | Average        |
| ≥ 40          | D     | Pass           |
| < 40          | F     | Fail           |

---

## 🤝 Contributing
1. Fork the repository
2. Create a branch: `git checkout -b feature/new-feature`
3. Commit changes: `git commit -m 'Add feature'`
4. Push to branch: `git push origin feature/new-feature`
5. Open a Pull Request

---

## 📜 License
[MIT License](LICENSE) © 2025 Your Name  
![Java](https://img.shields.io/badge/Java-17%2B-blue?logo=openjdk)

---

## 🙌 Acknowledgements
- **Strathmore University** for grading system guidelines
- Built with ☕ **Java** passion!
```

---

### 🔗 GitHub Tips
1. Add this README to your repo root as `README.md`
2. Include a `.gitignore` file for Java (exclude `.class` files)
3. Use GitHub’s "Preview" mode to check formatting
4. Add screenshots of the program output for better documentation! 📸

Let me know if you need help customizing it further! 😊
