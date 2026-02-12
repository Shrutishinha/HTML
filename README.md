Resume Analyzer

Frontend Project using HTML, CSS, and JavaScript

Overview

Resume Analyzer is a browser-based web application built using HTML, CSS, and Vanilla JavaScript. The application performs client-side, keyword-based resume analysis to evaluate technical skill presence and provide basic improvement suggestions.

All processing is performed locally in the user’s browser. The system does not use any backend services, artificial intelligence, machine learning, or external libraries.

This project is designed to demonstrate frontend development skills, JavaScript logic, and client-side file handling.

Key Features

Fully frontend-based application

No backend or server dependency

Resume upload and text input support

Keyword-based skill detection

Basic resume scoring system

ATS-oriented keyword evaluation

Improvement suggestions

Clean and responsive user interface

Offline functionality

How the Resume Analysis Works

The resume analysis is implemented using rule-based and deterministic logic in JavaScript.

Resume content is loaded using the FileReader API

Text is normalized (lowercase conversion and symbol removal)

Keywords are matched against predefined skill sets

A score is calculated based on matched keywords

Missing or weak skill areas are identified

Results are dynamically displayed in the UI

This approach demonstrates core JavaScript concepts such as string processing, conditional logic, and DOM manipulation.

Technology Stack
Technology	Purpose
HTML5	Structure and layout
CSS3	Styling and responsiveness
JavaScript (ES6)	Analysis logic and UI updates
FileReader API	Resume file reading
Project Structure
resume-analyzer/
│
├── index.html        # Main user interface
├── style.css         # Styling and layout
├── script.js         # Resume analysis logic
├── assets/           # Images and icons
└── README.md         # Project documentation

Skills Evaluated

The following technical skills are evaluated using keyword matching:

HTML, CSS, JavaScript

React (keyword-based detection)

Java, Python

SQL, MongoDB

Git and GitHub

Basic Data Structures concepts

Skill lists and scoring weights can be customized in script.js.

Running the Project Locally
Step 1: Clone the Repository
git clone https://github.com/your-username/resume-analyzer.git

Step 2: Navigate to the Project Folder
cd resume-analyzer

Step 3: Open the Application

Open index.html in any modern web browser.

No installation or setup is required.

No dependencies

No configuration

Works offline

Intended Use

Frontend development practice

Academic or mini-project submission

Learning client-side file handling

Demonstrating JavaScript logic and UI skills

Portfolio project for beginner to intermediate developers

Limitations

Keyword-based analysis only

No semantic or contextual understanding

No OCR support for scanned resumes

No real ATS integration

No machine learning or NLP

Limited PDF text extraction

Future Enhancements

Resume and job description comparison

Improved PDF text extraction

Role-based skill selection

Downloadable analysis reports

Backend integration using Node.js

User profile management

Author

Shruti
Frontend Developer
Skills: HTML, CSS, JavaScript, Data Analysis
