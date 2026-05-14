# InterviewReady 🎯

**Know Your Interview Readiness in Under 2 Minutes**

An innovative web tool that helps students objectively evaluate their interview preparation and get a personalized improvement plan before facing real recruiters.

---

## ✨ Features

- Ultra-fast assessment (Less than 2 minutes)
- PDF Resume Analysis using Apache PDFBox
- Overall Interview Readiness Score (0-100)
- Detailed breakdown of 4 categories: Technical, Resume, Communication, Portfolio
- Personalized Action Plan with priorities
- Clean, modern and beautiful UI
- Single-file Java Backend (Easy for submission)

---

## Tech Stack

| Component  | Technology                              |
|------------|-----------------------------------------|
| Backend    | Java 21 + Spring Boot 3.3               |
| Frontend   | React 18 + Vite + Tailwind CSS          |
| Resume Parser | Apache PDFBox                        |
| Build Tool | Maven (Backend) + npm (Frontend)        |

---

## Project Structure
interview-ready/
├── backend/
│   ├── pom.xml
│   └── src/main/java/com/interviewready/InterviewReady.java
├── frontend/
│   ├── package.json
│   ├── vite.config.js
│   ├── tailwind.config.js
│   ├── src/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── index.html
├── README.md
└── demo-video-script.md (optional)


---

## How to Run the Project

### 1. Backend

```bash
cd backend

# Install dependencies and run
./mvnw spring-boot:run
cd frontend

npm install
npm run dev

API Endpoint
POST http://localhost:8080/api/assess/submit
Content-Type: multipart/form-data
Request Fields:











































































FieldTypeDescriptionfullNameStringStudent's full nameemailStringEmail addressbranchStringCSE, IT, ECE, etc.graduationYearString2025, 2026, etc.javaLevelInteger (1-5)Java / OOP ratingpythonLevelInteger (1-5)Python ratingdsaLevelInteger (1-5)DSA ratingsystemDesignLevelInteger (1-5)System Design ratingdbmsLevelInteger (1-5)DBMS/SQL ratingprojectsCountIntegerNumber of good projectsportfolioUrlStringGitHub / Portfolio linkcommunicationSelfInteger (1-5)Self-rated communicationresumeFile (PDF)Resume PDF (Recommended)

Scoring Logic
Overall Score = Weighted Average

Technical Skills → 40%
Resume Quality → 25%
Communication → 20%
Projects & Portfolio → 15%

Readiness Levels

























Score RangeLevel85 - 100Excellent - Job Ready70 - 84Good - Ready with Minor Prep50 - 69Average - Needs Focused ImprovementBelow 50Beginner - Significant Preparation Needed

Screenshots
(Add screenshots of your running application here)

Home / Step 1 Screen
Skills Rating Screen
Resume Upload Screen
Final Score & Action Plan Screen


Future Enhancements

AI-powered resume analysis
User authentication and result history
PDF report download
Mock interview integration


Made With ❤️
For Students, By Students
Perfect for:

Final Year Academic Project
Hackathon Submission
Personal Portfolio
Campus Placement Preparation


Thank You!
