# Applicant-Score-Public

ApplicantScore is an AI-powered resume screening tool designed to streamline the hiring process for recruiters. It allows bulk uploading of resumes, analyzes them using advanced semantic analysis powered by OLlama, and provides a score for each applicant based on their fit for a given job description. This significantly reduces the time and effort spent on manual resume screening, enabling recruiters to focus on more strategic aspects of hiring.

## Technologies Used:
- Frontend:
  - React.js
  - Material-UI
  - Axios
  - XLSX (for Excel file handling in bulk upload)
  - React Quill (Rich Text Editor)
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

### Prerequisites
- Node.js
- Oracle Java or JDK
- API key from Ollama for LLM integration

### Steps to Run
1. Clone the repository
2. Go to frontend: ```cd frontend```
3. Then execute ```npm install```
4. Ollama API URL in application.properties from backend
5. Then start the application from frontend, execute ```npm run dev```
6. And run **HrBackendApplication** file from backend
7. Kudos!!! You can check in browser by going to url: **http://localhost:5173/**

## Demo
1. Job Creation Page: (http://localhost:5173/) 
<img width="1440" alt="Screenshot 2025-01-23 at 9 15 43 PM" src="https://github.com/user-attachments/assets/13b07d4a-6604-4b8d-921a-5505cf986fb2" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 16 14 PM" src="https://github.com/user-attachments/assets/2a80cdf2-0f32-4aaf-9dc1-ff2f020a0dcc" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 17 04 PM" src="https://github.com/user-attachments/assets/1924620b-f421-4c2b-a07b-f17fb0669b76" />

2. Job Manager Page(For editing and adding new questions): (http://localhost:5173/jobs/edit/13)
<img width="1440" alt="Screenshot 2025-01-23 at 9 18 36 PM" src="https://github.com/user-attachments/assets/c2567175-7ca3-4f73-90ec-79358f111571" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 19 18 PM" src="https://github.com/user-attachments/assets/3b22aaf1-b850-47b3-a2d1-6f469c44da6b" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 19 49 PM" src="https://github.com/user-attachments/assets/6d1f566a-2483-497f-9115-bfc678cac055" />

3. All Jobs List: (http://localhost:5173/jobs)
<img width="1440" alt="Screenshot 2025-01-23 at 9 20 33 PM" src="https://github.com/user-attachments/assets/b73f0900-bd12-4bc6-85ad-0bd5d22f8fb9" />

4. All Candidates List: (http://localhost:5173/candidates)
For Privacy Concerns Photo has been removed (As Candidates name, email, phone number, linkedin url, github url, and some actions like view, edit, delete candidates detials are displayed in a table that has Pagination, Sorting, Filtering)

5. Job Application Page: (http://localhost:5173/job-application)
<img width="1440" alt="Screenshot 2025-01-23 at 9 23 30 PM" src="https://github.com/user-attachments/assets/51df442d-20b0-47f2-a194-1678aec52710" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 24 31 PM" src="https://github.com/user-attachments/assets/f177f3c8-b360-48cf-a8e6-f634e4d58e58" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 24 17 PM" src="https://github.com/user-attachments/assets/a1009b2f-fdb8-4a10-8856-b4b21bdf7220" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 25 01 PM" src="https://github.com/user-attachments/assets/1c543603-3c72-4cd8-a90d-c7ad20f1b13a" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 27 47 PM" src="https://github.com/user-attachments/assets/a921521d-a00c-45ce-a20a-312e61a259f6" />

6. Bulk Upload Resumes Page: (http://localhost:5173/bulk-upload)
<img width="1440" alt="Screenshot 2025-01-23 at 9 28 25 PM" src="https://github.com/user-attachments/assets/ee4b616d-309f-400e-8d2e-d34f2f43ac44" />
<img width="1440" alt="Screenshot 2025-01-23 at 9 29 25 PM" src="https://github.com/user-attachments/assets/6db38262-2608-4331-94da-f5b5ded71778" />
Again For privacy concerns can not update Bulk Upload resumes, as candidates privacy is being violated, so only final ATS Scores, matching Keywords are displayed below they can be downloaded as Excel files and search and sort options are provided in website already.
<img width="721" alt="Screenshot 2025-01-23 at 9 33 49 PM" src="https://github.com/user-attachments/assets/5d00e23b-000a-4826-b16c-729cd496117d" />


## Future Enhancements
The following enhancements are planned for future releases (mentioned in `src/routes/index.jsx`):

-   AI-generated custom questions.
-   Improved resume matching algorithm.
-   Reduced AI model response time.
-   Proctoring features for question answering.
-   "Eye" button for clarifications and action column in all component.

## Contact
If you have any questions or suggestions, feel free to reach out if you want to check out the code and test it:
- **Name:** Pavan Varanasi
- **Email:** <a href="mailto:pavanvaranasi2002@gmail.com">pavanvaranasi2002</a>
- **LinkedIn:** <a href="https://linkedin.com/in/pavanvaranasi02">pavanvaranasi02</a>
- **GitHub:** <a href="https://github.com/pavanvaranasi02">pavanvaranasi02</a>

## License
This project is licensed under the MIT License.
