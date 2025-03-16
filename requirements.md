# Nurse AI Matching System - Requirements and Scope Documentation

## 1. Project Overview

### 1.1 Objective
The purpose of this project is to design and implement an AI matching system that takes a job listing as input and returns a ranked list of nurse profiles based on how well they match the job's criteria. The goal is to streamline the recruitment process by automating candidate matching, reducing manual screening efforts, and improving the quality of candidate-job matches.

### 1.2 Data Sources
- **Job Descriptions Dataset:** Contains information about job requirements such as required skills, certifications, experience, educational background, location, and specialized areas.
- **Nurse Profiles Dataset:** Includes nurse-specific information such as skills, certifications, years of experience, educational background, location preferences, and specialized expertise.

## 2. Define Requirements and Scope

### 2.1 Clarify the Objective
- **Problem Statement:**  
  Develop an AI matching system that inputs a job listing and outputs a ranked list of nurse profiles, assigning a "fit score" based on the alignment between job requirements and nurse qualifications.
- **System Goals:**  
  - Efficient filtering and ranking of nurse profiles.
  - Reduction of manual screening efforts.
  - Increased accuracy in matching job requirements with nurse qualifications.

### 2.2 Identify Key Matching Criteria
Determine and document the attributes that are most important for matching nurses to job listings. Consider the following criteria:
- **Skills and Certifications:**  
  Identify if the nurse possesses the specific clinical and technical skills required for the job. Include any mandatory certifications.
- **Years of Experience:**  
  Compare overall clinical experience and experience in specialized areas relevant to the job.
- **Educational Background:**  
  Evaluate educational qualifications, degrees, and any additional training or licenses.
- **Location and Shift Preferences:**  
  Consider the nurse’s geographical location and availability for shifts (e.g., day, night, weekend).
- **Specialized Areas of Expertise:**  
  Match specialized skills (e.g., ICU, pediatrics, emergency care) with the job's requirements.

### 2.3 Set Business Goals & Define "Fit"
- **Definition of Fit:**  
  Establish what constitutes an ideal match between a nurse’s profile and a job listing. Decide if an exact match is required or if acceptable substitutes are allowed.
- **Thresholds and Minimum Requirements:**  
  Define any baseline criteria (e.g., a nurse must have a specific certification or a minimum number of years of experience).
- **Weighted Scoring System:**  
  Develop a scoring rubric to calculate a "fit score" that might include:
  - Skills and Certifications: 40%
  - Years of Experience: 25%
  - Educational Background: 15%
  - Location: 10%
  - Shift Preferences: 10%

  These weights can be adjusted based on stakeholder feedback and business priorities.



## 3. Next Steps
1. **Documentation Review:**  
   Share this document with all relevant stakeholders for feedback and approval.
2. **Data Exploration:**  
   Proceed to explore and understand the job descriptions and nurse profiles datasets to confirm the available attributes and identify any data cleaning or transformation requirements.





