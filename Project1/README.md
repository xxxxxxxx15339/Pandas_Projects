# 🟢 Project 1. Student Grades Analysis

## 📁 Dataset

Create a CSV file named **`students_grades.csv`** with the following sample data:

| Name    | Math | Physics | Chemistry |
|---------|------|---------|-----------|
| Sara    | 12   | 14      | 15        |
| Youssef | 9    | 8       | 10        |
| Imane   | 16   | 17      | 14        |
| Omar    | 13   | 12      | 11        |
| Amal    | 15   | 18      | 17        |
| Rachid  | 7    | 6       | 8         |
| Hajar   | 11   | 13      | 12        |

---

## 📄 Your Tasks

1. **Load** the CSV into a pandas DataFrame.
2. **Calculate** the average grade for each student (new column: `Average`).
3. **Sort** students by their average grade in descending order.
4. **Display** the top 3 students.
5. **Save** the sorted data into a new CSV file called `students_grades_with_average.csv`.

---

## 💡 Hints

- Use `pd.read_csv()`
- Create average:
  ```python
  df['Average'] = df[['Math', 'Physics', 'Chemistry']].mean(axis=1)
