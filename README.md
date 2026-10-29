# Student Attendance Lookup System

A web-based student attendance lookup application built using HTML, CSS, and JavaScript. Students can enter their registration number and date of birth to view their attendance information and calculated attendance percentage.

## Features

- **Student Lookup:** Enter a registration number and date of birth to look up a student record.
- **Attendance Calculation:** Calculate attendance percentage using attended classes and total classes.
- **Student Information:** Display available student details and the associated image.
- **Responsive Interface:** Styled layout designed for different screen sizes.
- **Academic Calendar:** Provides a link to the academic calendar.
- **GitHub Pages Deployment:** Hosted as a static website.

## Technologies Used

- HTML5 — webpage structure
- CSS3 — styling, layout, animations, and responsive design
- JavaScript — form handling, data lookup, and attendance calculation
- JSON — sample student records
- GitHub Pages — static website hosting

## Project Structure

```text
Attendance/
├── data/
│   └── users.json
├── 404.html
├── index.html
├── scripts.js
├── styles.css
└── README.md
```

## How It Works

1. Open the attendance website.
2. Enter a registration number and date of birth.
3. Submit the form.
4. The JavaScript code retrieves the matching record from the JSON data.
5. The application calculates the attendance percentage from the attendance totals.
6. The result is displayed in a popup.

## Run Locally

1. Download or clone this repository.
2. Keep the HTML, CSS, JavaScript, and data files in their expected locations.
3. Open `index.html` in a modern web browser, or use a local development server.
4. Test the lookup using the sample records.

The application uses browser-side JavaScript and static files; it does not currently provide a server-side authentication system.

## Data and Security Notice

This project is intended for demonstration and educational use. The JSON file is accessible to visitors of a public deployment, and browser-side validation does not provide secure authentication.

Use only fictional sample data in the public repository. Do not publish real student names, registration numbers, dates of birth, photographs, or attendance records.

## Future Enhancements

- Move student data to a secure backend and database.
- Implement server-side authentication and authorization.
- Improve input validation and error messages.
- Add automated tests for attendance calculations.
- Improve accessibility and mobile usability.
- Add documentation, architecture diagrams, and test reports.

## Project Status

The existing GitHub Pages deployment is reported to be working. Further changes should be tested to ensure that the attendance lookup and existing interface continue to function correctly.
