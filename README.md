# Exam-Seating-Arrangement

A simple Java program to arrange students into an exam hall seating layout based on user inputs like number of rows, columns, and total students. It displays a clear 2D seating plan and handles edge cases like insufficient seats.

---

## ✅ Features

- Accepts user input for number of rows, columns, and students
- Displays seating arrangement in a tabular grid
- Marks unoccupied seats as **Empty**
- Automatically assigns student IDs as **S1, S2, S3...**
- Input validation to prevent over-allocation
- Easy to modify or extend (e.g., randomized seating, exporting to file)

---

## 💻 Technologies Used

- Java (JDK 8 or above)
- Java Standard Libraries (Scanner, Arrays, File I/O)
- Command-line / Terminal

---

## 🗂️ Project Structure

ExamSeatingArrangement
1. ExamSeatingArrangement.java # Main Java source file
2. seating_arrangement.txt # (Optional) Output file if file export is added

---

▶️ How to Run the Program

1. Open terminal or command prompt
2. Compile the java program : javac ExamSeatingArrangement.java
3. Run the program : java ExamSeatingArrangement

---

🧾 Example Terminal Session

C:\Users\YourName\Documents> javac ExamSeatingArrangement.java
C:\Users\YourName\Documents> java ExamSeatingArrangement
Enter number of rows: 3
Enter number of columns: 4
Enter number of students: 10

Seating Arrangement:
S1      S2      S3      S4
S5      S6      S7      S8
S9      S10     Empty   Empty
