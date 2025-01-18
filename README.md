# Applicant-Score-Public

ApplicantScore is an AI-powered resume screening tool designed to streamline the hiring process for recruiters. It allows bulk uploading of resumes, analyzes them using advanced semantic analysis powered by OLlama, and provides a score for each applicant based on their fit for a given job description. This significantly reduces the time and effort spent on manual resume screening, enabling recruiters to focus on more strategic aspects of hiring.

## Technologies Used:
- Frontend:
  - React.js
  - Material-UI
- Backend:
  - Java
  - Spring Boot
- AI Integration:
  - Ollama LLM API
- Database:
  - MySQL
- Other Tools:
  - REST APIs for CRUD operations

## Features
- **AI-Powered Job Creation:** Refines and extracts key requirements (skills, education, experience) from job descriptions using Ollama's LLM API.
- **Interactive Job Description:** Editable accordions for skills, education, and experience, with seamless job creation functionality.
- **Resume Analysis:** Upload a resume to extract structured details and calculate ATS scores by comparing it with job descriptions.
- **Bulk Resume Upload:** Placeholder for future enhancement to score multiple resumes at once based on a job description.
- **Candidate and Job Management:** Full CRUD operations for managing candidates and job postings in dedicated pages.
- **Future-Proof Features:** Supports adding application questions and integrates planned proctoring functionality.

## Future Features
- **Bulk Resume Scoring**:
  - Automate scoring for multiple resumes in one upload.
- **Proctoring**:
  - Integrate proctoring during job applications.
- **CRUD Operations On Application**:
  - To check if any candidate already applied for the job and trying to apply for the second time.
- **Enhanced AI Insights**:
  - Further refine job descriptions and candidate analysis with advanced AI capabilities.

## Installation and Setup

### Prerequisites
- Node.js
- API key from Ollama for LLM integration

### Steps to Run
1. Clone the repository
2. Go to frontend: ```cd frontend```
3. Then execute ```npm install```
4. Ollama API URL in application.properties from backend
5. Then start the application from frontend, execute ```npm run dev```
6. And run **HrBackendApplication** file from backend
7. Kudos!!! You can check in browser by going to url: **http://localhost:5173/**

## License
This project is licensed under the MIT License.

## Contact
If you have any questions or suggestions, feel free to reach out if you want to check out the code and test it:
- **Name:** Pavan Varanasi
- **Email:** <a href="mailto:pavanvaranasi2002@gmail.com">pavanvaranasi2002</a>
- **LinkedIn:** <a href="https://linkedin.com/in/pavanvaranasi02">pavanvaranasi02</a>
- **GitHub:** <a href="https://github.com/pavanvaranasi02">pavanvaranasi02</a>

## Demo
1. Job Creation Page: http://localhost:5173/  
<img width="1440" alt="Screenshot 2025-01-17 at 3 38 30 PM" src="https://github.com/user-attachments/assets/35ddbbbd-782c-4e08-8d74-d4843ce90b39" />
<img width="1439" alt="Screenshot 2025-01-17 at 3 40 51 PM" src="https://github.com/user-attachments/assets/69fbf222-bbcd-44af-a4f6-9490136a8b9d" />

2. Job Application Page: http://localhost:5173/job-application
<img width="1435" alt="Screenshot 2025-01-17 at 3 42 07 PM" src="https://github.com/user-attachments/assets/3d10cf97-8db5-476c-b65f-cc097a2ae887" />
<img width="1440" alt="Screenshot 2025-01-17 at 3 42 40 PM" src="https://github.com/user-attachments/assets/5d44f607-7c5a-4595-b70a-5800995ba886" />
<img width="1440" alt="Screenshot 2025-01-17 at 3 46 42 PM" src="https://github.com/user-attachments/assets/26b5ac0b-4aba-4c70-9717-6c81c335c9f1" />

3. Bulk Upload Resume: http://localhost:5173/bulk-upload
<img width="1440" alt="Screenshot 2025-01-17 at 3 47 19 PM" src="https://github.com/user-attachments/assets/5b209219-ccad-4ab3-8191-0476e68a0819" />

4. Job List: http://localhost:5173/jobs
<img width="1440" alt="Screenshot 2025-01-17 at 3 48 14 PM" src="https://github.com/user-attachments/assets/3cb7b414-9064-4234-83be-98d0db8946b7" />

