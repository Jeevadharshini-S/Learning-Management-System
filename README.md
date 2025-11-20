Learning Management System (Full-Stack)
A full-stack Learning Management System (LMS) built using React (frontend) and Spring Boot (backend).The platform allows users to sign up, log in, browse courses, enroll, track progress, take quizzes, add courses, and more — all through a beautiful modern UI.This LMS is designed to provide a smooth learning experience for students, instructors, and admins

INSTRUCTUR FEATURES

🔹Add new courses
🔹Provide course descriptions
🔹Add quiz questions
🔹Edit or delete courses

STUDENT FEATURES

🔹Create account & login
🔹Browse all courses
🔹Enroll into courses
🔹View course details
🔹Take quizzes and see results
🔹Track learning progress (%)

UI FEATURES

🔹Modern premium dark UI design
🔹Smooth navigation
🔹Fully responsive layout

TECH STACK
🔹Frontend (React)
🔹React.js
🔹React Router
🔹CSS
🔹Axios

BACKEND (Spring Boot)

🔹Spring Boot
🔹Spring Web
🔹Spring Data JPA
🔹MySQL

FOLDER STRUCTURE
Learning-Management-System/
│
├── reactapp/              # Frontend (React)
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Auth.js
│   │   │   ├── Home.js
│   │   │   ├── ProgressTracker.js
│   │   │   ├── QuizPage.js
│   │   │   ├── EnrollmentPage.js
│   │   │   ├── PremiumCourse.js
│   │   │   ├── AddCourse.js
│   │   │   └── other components...
│   │   ├── App.js
│   │   ├── index.js
│   │   └── App.css
│   ├── package.json
│   └── package-lock.json
│
└── springapp/             # Backend (Spring Boot)
    ├── src/
    │   ├── main/java/com/example/springapp/
    │   │   ├── controller/
    │   │   ├── service/
    │   │   ├── model/
    │   │   └── repository/
    │   └── resources/
    ├── Dockerfile (optional)
    └── pom.xml

INSTALLATION & SETUP
🔹 1. Clone the repository
      git clone https://github.com/Jeevadharshini-S/Learning-Management-System.git
cd Learning-Management-System

BACKEND SETUP (Spring Boot)
🔹 Go to backend folder:
    cd springapp
    mvn spring-boot:run
    http://localhost:8080/

FRONTEND SETUP (React)
🔹 Go to the reactapp folder:
    cd reactapp
    npm install
    npm start
   http://localhost:8001/

FUTURE ENHANCEMENT

🔹JWT Authentication (Secure Login)
🔹Admin Dashboard
🔹Video Lessons Module
🔹Chat/Discussion Forum
🔹Certificates Generation
🔹AI-based course recommendations   
