# Student Grade Calculator Using Python

## 📌 Project Overview

The **Student Grade Calculator** is a beginner-friendly Python project developed as part of my internship learning journey at **Veda Technology**.

The program stores student marks in a Python list and assigns a grade to each student using conditional statements (`if`, `elif`, and `else`).

## 🎯 Objectives

- Store multiple students' marks using a Python list.
- Assign grades based on predefined mark ranges.
- Display each student's marks and corresponding grade.
- Practice conditional statements and loops.
- Handle invalid marks.

## 🛠️ Technologies Used

- Python 3
- Google Colab
- Jupyter Notebook
- GitHub

## 📂 Project Structure

```text
Student-Grade-Calculator/
├── Student_Grade_Calculator.ipynb
└── README.md
```

## ⚙️ Grading Criteria

| Marks Range | Grade |
|---|---|
| 90–100 | A |
| 80–89 | B |
| 70–79 | C |
| 50–69 | D |
| Below 50 | F |
| Outside the valid range | Invalid Marks |

**Note:** The program uses marks from 1 to 100 as valid input. Marks below 1 or above 100 are reported as invalid.

## 💻 Python Code

```python
# Student Grade Calculator

# Store student marks in a list
marks_list = [100, 84, 73, 37, 51, 66, 81, 70, 66]

print("Student Grade Report")
print("-" * 35)

for i, marks in enumerate(marks_list, start=1):

    if marks < 1 or marks > 100:
        grade = "Invalid Marks"
    elif marks >= 90:
        grade = "A"
    elif marks >= 80:
        grade = "B"
    elif marks >= 70:
        grade = "C"
    elif marks >= 50:
        grade = "D"
    else:
        grade = "F"

    print(f"Student {i}: Marks = {marks}, Grade = {grade}")
```

## 📊 Sample Output

```text
Student Grade Report
-----------------------------------
Student 1: Marks = 100, Grade = A
Student 
