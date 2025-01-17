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
<img width="1440" alt="Screenshot 2025-01-17 at 1 11 25 PM" src="https://github.com/user-attachments/assets/bbefd62c-267c-4245-985e-3afc22380f01" />
<img width="1440" alt="Screenshot 2025-01-17 at 1 13 00 PM" src="https://github.com/user-attachments/assets/f56579e6-df29-4ed9-9b72-f7762ed77373" />
<img width="1434" alt="Screenshot 2025-01-17 at 1 13 32 PM" src="https://github.com/user-attachments/assets/144484b6-88a3-4557-8b8b-b7b44afb2d89" />

2. Job Application Page: http://localhost:5173/job-application
<img width="1440" alt="Screenshot 2025-01-17 at 1 15 08 PM" src="https://github.com/user-attachments/assets/8815ee25-0576-4109-b5c1-06616f77e0de" />
<img width="1440" alt="Screenshot 2025-01-17 at 1 15 35 PM" src="https://github.com/user-attachments/assets/51afd8e5-8d67-49db-b0f2-15d091183858" />
<img width="1440" alt="Screenshot 2025-01-17 at 1 15 55 PM" src="https://github.com/user-attachments/assets/872baed0-80b4-456e-b0c9-9e545de306ae" />
<img width="1417" alt="Screenshot 2025-01-17 at 1 16 28 PM" src="https://github.com/user-attachments/assets/17cf5d0b-fc70-4814-a00c-f084863dfed6" />
<img width="1440" alt="Screenshot 2025-01-17 at 1 18 42 PM" src="https://github.com/user-attachments/assets/82d853b6-51c2-4a5a-8e0b-d8ac3c2c7b67" />

3. Bulk Upload Resume: http://localhost:5173/bulk-upload
<img width="1440" alt="Screenshot 2025-01-17 at 1 19 20 PM" src="https://github.com/user-attachments/assets/42c52ac2-de7f-47f6-bc6c-c800cfdc5ffc" />

4. Candidates List: http://localhost:5173/candidates
<img width="1440" alt="Screenshot 2025-01-17 at 1 20 38 PM" src="https://github.com/user-attachments/assets/1862a216-3e25-4849-9af5-32f4a8b3199a" />

5. Job List: http://localhost:5173/jobs
<img width="1440" alt="Screenshot 2025-01-17 at 1 21 38 PM" src="https://github.com/user-attachments/assets/f55ad237-1ce6-4a07-a738-8764da95ba56" />
