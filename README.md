# Online-Quiz-App
The Online Quiz Application is a web-based platform built using Spring Boot for the backend and HTML, CSS, and JavaScript for the frontend. It allows users to attempt a multiple-choice quiz, submit their answers, and instantly view their scores. An admin panel is also provided to manage quiz questions.

Key Features:

User Quiz Interface:
Displays a list of multiple-choice questions fetched from the backend.
Allows users to select answers and submit them.
Displays total score and number of correct answers immediately after submission.

Admin Panel:

Allows admins to add new quiz questions with multiple options.
Stores questions in the backend for dynamic retrieval.

Backend (Spring Boot):

REST APIs for:

Fetching quiz questions (/api/quiz/questions).
Submitting quiz answers and calculating scores (/api/quiz/submit).
Adding questions (admin functionality).
Uses in-memory storage or a database (optional) for quiz questions.

Frontend (HTML, CSS, JS):

index.html – Main quiz page for users.
admin.html – Admin dashboard for adding questions.
CSS stylesheets for responsive and clean UI.
JavaScript for dynamic question rendering and API communication.

Tools & Technologies:

Backend: Java, Spring Boot, Maven
Frontend: HTML5, CSS3, JavaScript (Fetch API)

IDE:  Eclipse

Server: Embedded Tomcat (Spring Boot default)

Workflow:

User side:

Opens the quiz page.
Questions are fetched from the backend.
User selects answers and clicks Submit.
Backend processes the submission and returns score.

Admin side:

Opens admin panel.
Adds new questions with multiple options and the correct answer index.
Questions are saved in backend memory or database.

Possible Enhancements:

Add a database (MySQL/PostgreSQL) for persistent question storage.
Add user login system with roles (User/Admin).
Add timer-based quizzes.
Track past scores for each user.
