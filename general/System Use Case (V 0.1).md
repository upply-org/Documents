#  Upply — Use Case Specification

---

## **Actors**

| Actor          | Description                                                          |
| -------------- | -------------------------------------------------------------------- |
| **User**       | A general system user who can be either a Job Seeker or a Recruiter. |
| **Job Seeker** | A user looking for job opportunities.                                |
| **Recruiter**  | A user posting jobs and reviewing applicants.                        |
| **System**     | The job portal platform that manages users, jobs, and applications.  |
##  **Job Seeker Use Cases**

| Use Case                                         | Description                                                                                        |
| ------------------------------------------------ | -------------------------------------------------------------------------------------------------- |
| **UC1 – Register & Select User Type**            | The user creates an account and chooses their role: _Job Seeker_ or _Recruiter_.                   |
| **UC2 – Create Profile**                         | The seeker adds details: name, university, communication links, skills, experience, and projects.  |
| **UC3 – Edit Profile**                           | The seeker can update or modify profile information anytime.                                       |
| **UC4 – Browse Jobs**                            | The seeker views available job listings with filters like location, tech skills, or organization.  |
| **UC5 – View Job Details**                       | The seeker views job-specific details such as description, required skills, and organization info. |
| **UC6 – Apply for Job**                          | The seeker applies for a job using either their saved profile data or by uploading a resume.       |
| **UC7 – Auto-fill Application Form** _(include)_ | When applying, the system auto-fills basic information from the seeker’s profile.                  |
##  **Recruiter Use Cases**

|Use Case|Description|
|---|---|
|**UC8 – Create Profile**|The recruiter enters details such as organization name, organization URL, and about section.|
|**UC9 – Create Job Posting**|The recruiter creates a job by entering title, description, required tech skills, and location.|
|**UC10 – Customize Application Form**|The recruiter adds specific questions or fields to the job application form.|
|**UC11 – Manage Job Postings**|The recruiter can edit, update, or delete existing job postings.|
|**UC12 – View Applicants**|The recruiter views all applicants for a job.|
|**UC13 – Sort Applicants** _(include)_|The system sorts or ranks applicants automatically based on resume–job match.|
