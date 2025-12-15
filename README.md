# 🧮 CGPA Calculator

This project is a single-file web application (`.html`) designed to help Nigerian university students quickly estimate their Cumulative Grade Point Average (CGPA) based on their semester results.

## 🌟 Features

- **Yearly/Session Tracking**: Easily track and calculate results across multiple academic sessions.
- **Semester Input**: Accepts inputs for both 1st and 2nd semesters for each year.
- **Simplified Calculation**: Uses a simple average of all recorded Semester GPAs.
- **Degree Classification**: Automatically determines the corresponding degree class (e.g., First Class, 2:1, 2:2) based on the calculated CGPA.
- **Responsive Design**: Works well on both desktop and mobile devices.

## 💡 How It Works

This calculator uses a **Simple Average** method, calculating the total sum of all your semester GPAs and dividing it by the total number of semesters recorded.
CGPA = (Sum of all Semester GPAs) / (Total number of Semesters)


## ⚠️ Important Note on Accuracy (The Difference Between Simple vs. Weighted Average)

The standard method used by most Nigerian universities is the **Weighted Average**, which requires inputting the **Total Credit Units (T.C.U)** for each semester.

- **In a real Nigerian university calculation**: A semester where you had 25 credit units and scored a 5.0 GPA contributes more to your final CGPA than a semester where you had 15 credit units and scored a 5.0 GPA.
- **In this Simplified Calculator**: We are assuming that the credit units for every semester are equal. This method provides a quick estimate but might be slightly inaccurate if your credit load varies significantly between semesters.

## 🚀 Usage

1. **Save the File**: Save the HTML, CSS, and JavaScript code into a single file named `cgpa_calculator.html`.
2. **Open in Browser**: Open `cgpa_calculator.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. **Input Data**:
   - Enter your Semester GPA (on the 5.0 scale, e.g., 4.35) into the corresponding semester fields.
   - Leave any semester fields blank if you have not yet seen the result (e.g., if you are currently in 400 Level, leave Year 4, 2nd Semester blank).
4. **Add/Remove Years**: Use the "Add Year" button to include more academic sessions (e.g., for a 5-year or 6-year course). Use the trash icon to remove an entire year's input.
5. **Calculate**: Click the "Calculate CGPA" button to view the overall CGPA and the corresponding degree classification.

## 🎓 Degree Classification (5.0 Scale)

The calculator uses the following common Nigerian university classification thresholds:

| CGPA Range          | Degree Class                 |
| ------------------- | ---------------------------- |
| ≥ 4.50              | First Class Honours          |
| 3.50 – 4.49         | Second Class Upper (2:1)     |
| 2.40 – 3.49         | Second Class Lower (2:2)     |
| 1.50 – 2.39         | Third Class                  |
| 1.00 – 1.49         | Pass                         |
| < 1.00              | Probation / Fail             |
