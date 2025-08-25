# AI_CAREER_NAVIGATOR

**📌 Overview**

AI Career Navigator is a web-based intelligent system designed to guide students and professionals in discovering the most suitable career paths. The platform uses Artificial Intelligence (AI) to predict career roles, recommend personalized courses, projects, and certifications, while also tracking progress to ensure users stay aligned with their goals.

**🎯 Objective**

Many students and job seekers struggle to identify the right career path and access relevant resources. This project addresses the challenge by:

✅ Predicting suitable career roles using AI.

✅ Recommending personalized learning paths (courses, projects, certifications).

✅ Tracking progress with visual dashboards.

✅ Verifying certificate authenticity using OCR.

**🛠️ Proposed Solution**

The system is implemented as a smart web application with the following features:

Career Prediction – Uses a Random Forest model to suggest the top 3 roles based on user-rated skills.

Tech: Python, Scikit-learn

Course & Project Recommendation – Provides role-specific learning paths with step-by-step guidance.

Tech: React.js

Progress Tracking – Displays progress bars for courses/projects.

Tech: React.js, Chart.js

Certificate Upload & OCR Verification – Extracts and verifies text from uploaded certificates.

Tech: OCR, Python

**🏗️ System Architecture**

The project consists of five core modules:

User Interface (React.js) – Login, skill rating, career selection, dashboard view.

Career Prediction (Random Forest) – Suggests top 3 roles from user ratings.

Recommendation Engine – Recommends curated courses & projects.

Progress Tracker – Visual tracking of learning progress.

Certificate Management – Handles upload & OCR-based verification.

**⚙️ Tech Stack**

Frontend: React.js

Backend: Python (Flask)

Database: Firestore

Machine Learning: Random Forest, Scikit-learn, Pandas, NumPy

Visualization: Chart.js

OCR: Python OCR libraries

Version Control: GitHub


<img width="828" height="894" alt="image" src="https://github.com/user-attachments/assets/7014e319-673d-4ec9-85e0-0a96f590926c" />


**Work flow of the project**

  
  <img width="749" height="839" alt="image" src="https://github.com/user-attachments/assets/7b7a1c79-8c18-4bbb-82aa-3df30f286f24" />


**🌟 Key Features**

🔮 AI-Based Career Prediction – Suggests top 3 roles based on skills.

📚 Personalized Learning Path – Courses & projects tailored to chosen career role.

📊 Progress Dashboard – Track completion with visual progress bars.

🏅 Certificate OCR Verification – Auto-validates course completions.

👤 User Profile Management – Stores skills, career role, progress & certificates.

✍️ Manual Completion Option – Users can manually mark tasks as completed.

**🚧 Challenges Faced**

Data Bias – Initial career predictions were inaccurate due to limited datasets.
✅ Solution: Improved dataset diversity & aligned with real job market trends.

Dynamic Job Market – Career suggestions risked becoming outdated.
✅ Solution: Planned integration with job portal APIs (LinkedIn, Indeed).

Certificate Verification Issues – Different formats hindered OCR accuracy.
✅ Solution: Pre-processing & keyword-based matching with manual review fallback.

**📖 Learning Outcomes**

Hands-on experience with Machine Learning (Random Forest).

OCR integration for certificate text extraction & validation.

Web development with React, Firebase, Flask backend.

Data preprocessing, model tuning, & bias handling.

Team collaboration, UI/UX design, and project planning skills.

**🔮 Future Scope**

Integration with job market APIs (LinkedIn, Indeed) for real-time trends.

Advanced personalization with deep learning models.

AI-powered chatbot for career guidance.

Gamified progress tracking to boost engagement.

Expansion to mobile apps with multilingual support.

**Screenshot of the work**

![WhatsApp Image 2025-05-12 at 18 55 11_a3301efb](https://github.com/user-attachments/assets/aca4a15b-8175-407e-8d05-c399b02ddee9)
![WhatsApp Image 2025-05-12 at 18 55 11_f1f0f630](https://github.com/user-attachments/assets/87d61924-7c5b-4cc8-9636-b24564c504af)
<img width="1535" height="536" alt="image" src="https://github.com/user-attachments/assets/dd81db64-71f2-47ef-8fa3-e78591baa63f" />


**📌 How to Run the Project**

Clone the repository:

git clone https://github.com/Ha1r2i3n4i/AI_CAREER_NAVIGATOR.git
cd AI_CAREER_NAVIGATOR


Install dependencies (backend):

pip install -r requirements.txt


Run Flask server:

python app.py


Install frontend dependencies & run React app:

cd frontend
npm install
npm start


Open the app in your browser at http://localhost:3000.
