# 🚀 Interview AI - Your Personal Interview Strategist

An intelligent, full-stack MERN web application that analyzes your resume against a target job description to generate customized interview preparation reports using Google Gemini AI. 

Built to help candidates prepare smarter, this tool acts as a mock interviewer by generating highly relevant technical questions based on the user's actual project architecture and experience.

## ✨ Key Features

* **AI-Powered Resume Parsing:** Upload your resume (PDF) or write a self-description. The system extracts core competencies, tech stacks, and past project details.
* **Dynamic Match Scoring:** Get an instant compatibility score (out of 100%) indicating how well your profile aligns with the target job description.
* **Custom Question Generation:** Generates highly specific technical and behavioral questions tailored to *your* past projects and the specific job requirements.
* **Skill Gap Analysis:** Identifies missing skills required for the target role and provides a roadmap to bridge those gaps.
* **Secure User Authentication:** JWT-based login and signup system to securely save and access your past interview reports.

## 🛠️ Tech Stack

**Frontend:**
* React.js (Vite)
* SCSS (Custom Styling & Animations)
* Axios (API Communication)
* React Router DOM

**Backend:**
* Node.js & Express.js
* MongoDB Atlas & Mongoose
* Google Gemini API (`@google/genai`) for LLM processing
* Multer (File Upload Handling)
* `pdf-parse` (PDF Text Extraction)
* JSON Web Tokens (JWT) & bcrypt (Security)

## 🚀 Getting Started

### Prerequisites
Make sure you have the following installed/configured:
* Node.js (v18 or higher)
* MongoDB Atlas Database
* Google Gemini API Key

### Installation & Setup

**1. Clone the repository:**
```bash
git clone [https://github.com/anjali9555/AI-Interview.git](https://github.com/anjali9555/AI-Interview.git)
cd AI-Interview