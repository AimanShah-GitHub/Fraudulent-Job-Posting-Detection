# Fraudulent-Job-Posting-Detection
In this project, we will make a predictive model based on the dataset provided to predict whether a job post is fake or real.

## Approach
We have used a 'fraudulent' attribute provided for classification. In the problem statement, it was mentioned that "This dataset contains 18K job descriptions out of which about 800 are fake". We knew the count of fake jobs i.e. 800 so we calculated the count for real job (using the fraudulent attribute) and we gathered the information that around 17014 jobs are real and the parameteres for this analysis was 0 and 1. 

0 for job post that were not fraudulent and 1 for the jobs that were fraudulent. 

## Information about the data
job_id: Unique Job ID

title: The title of the job ad entry.

location: Geographical location of the job ad.

department: Corporate department (e.g. sales).

salary_range: Indicative salary range (e.g. $50,000-$60,000)

company_profile: A brief company description.

description: The details description of the job ad.

requirements: Enlisted requirements for the job opening.

benefits: Enlisted offered benefits by the employer.

telecommuting: True for telecommuting positions.

has_company_logo: True if company logo is present.

has_questions: True if screening questions are present.

employment_type: Full-type, Part-time, Contract, etc.

required_experience: Executive, Entry level, Intern, etc.

required_education: Doctorate, Master’s Degree, Bachelor, etc.

industry: Automotive, IT, Health care, Real estate, etc.

function: Consulting, Engineering, Research, Sales etc.

fraudulent: target - Classification attribute.
