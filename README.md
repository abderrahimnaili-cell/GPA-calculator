# 🎓 GPA Calculator (University Average Calculator)

A modern, responsive, and user-friendly web application designed to help university students calculate their semester Grade Point Average (GPA) accurately and effortlessly. 

This project replaces the traditional "pen and paper" method with a sleek Dark Mode interface, eliminating calculation errors and saving time.

## ✨ Features

*   Dynamic Rows: Easily add or remove subjects using the + ADD SUBJECT and X buttons.
*   Flexible Grading: Supports final exams (Exam), Tutorials (TD), and Practical Work (TP) inputs.
*   Instant Calculation: Calculates the Weighted Average automatically based on subject coefficients.
*   Modern UI/UX: Features a sleek Dark Mode with neon gradient accents to reduce eye strain.
*   Dynamic Feedback: Displays a popup modal with the final average and an encouraging message based on the score (e.g., "Excellent! 🏆").
*   Responsive Design: Fully functional on desktops, tablets, and mobile devices.

## 🛠️ Technologies Used

*   HTML5: For the structural skeleton of the application.
*   CSS3: For styling, layout (Flexbox/Grid), and the dark-themed user interface.
*   JavaScript (ES6): For DOM manipulation (adding/deleting rows) and the core mathematical logic.

## 🧮 How the Calculation Works

The application uses the standard Weighted Average formula used in universities:

\[
 \text{GPA} = \frac{\sum (\text{Subject Final Grade} \times \text{Coefficient})}{\sum \text{Coefficients}} 
\]

1. It evaluates the final grade for each subject (taking into account the specific percentages for Exam, TD, and TP).
2. It multiplies each subject's grade by its respective coefficient.
3. It sums all the resulting values (Total Points).
4. It divides the Total Points by the sum of all Coefficients to get the final GPA.
5. The result is rounded to two decimal places for accuracy.

## 🚀 How to Run the Project Locally

Since this is a front-end project, you don't need any complex installations. 

1. Clone the repository:
   `bash
  
