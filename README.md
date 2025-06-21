# 🎓 Student Management System (Bash Script)
A terminal-based Student Management System written in Bash that simulates a basic academic management portal for students, teachers, and administrators. It handles semester creation, course enrollment, student records, teacher assignments, and grading — all through a simple command-line interface using CSV files as a backend.

## 📌 Features

### 🔐 Admin Panel (Password: admin)
- Create/view/delete **students**
- Create/view **teachers**
- Create/view **semesters**
- Create/view **courses**
- Enroll students into courses
- Modify assigned teacher for a course
- View all student enrollments with marks
- Search students by ID and view results
- Full report of each student’s performance
- Delete student from the system

### 🧑‍🏫 Teacher Panel
- View list of students enrolled in their courses
- Enter or update marks:
  - Attendance (Max: 15)
  - Quiz (Max: 15)
  - Midterm (Max: 30)
  - Final (Max: 40)

### 👩‍🎓 Student Panel
- View their own course-wise performance
- Grades are calculated and shown based on total marks:
  - `A+` (≥80), `A` (≥75), `A-` (≥70), down to `F` (<40)

## 🛠️ Technologies Used

- **Bash Shell Scripting**
- **CSV file-based storage** (no database required)
## 📁 File Structure

- `student.sh`: Main script file (run this)
- `student.csv`: Student records
- `teacher.csv`: Teacher records
- `semester.csv`: Semester information
- `course.csv`: Course details
- `courseEnroll.csv`: Course enrollment & marks

> ⚠️ These `.csv` files are created as needed when the script runs.

For any queries, suggestions, or contributions, feel free to contact me!

