#Smart-Expense-Tracker

**A C++ console application to manage student records and track their monthly expenses.**

---

## Features

### Student Management
- Add new students with:
  - Student ID
  - Name
  - Registration date
  - Phone number
  - Monthly budget
- View all registered students
- Search and update student information
- Sort students alphabetically by first name

### Expense Tracking
- Add expenses with:
  - Category (e.g., `school_fee`, `food`, `transport`, `entertainment`, `other`)
  - Amount
  - Date
  - Description
- View total expenses per student
- Delete a student's expense
- Sort expenses by amount
- Warn if expenses exceed monthly budget

### Reporting
- Generate individual budget reports (total spent and remaining budget)
- Export all expenses to `expenses_report.csv`

---

## File Structure

- `students.txt` — Stores student records
- `expenses.txt` — Stores expense records
- `expenses_report.csv` — Output file for exported expense data

---

## How to Compile and Run

### Using G++:

```bash
g++ -o student_expense main.cpp
./student_expense