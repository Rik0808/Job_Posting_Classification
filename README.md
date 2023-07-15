# Job_Posting_Classification
Exploratory data analysis on Fake Job Description dataset in Kaggle in an attempt to understand how to classify them into fraud and real posting.
## **Intro and Overview of the Problem:**
The Internet is so full of fake articles, news, documents, and whatnot and the bad news is probably the number of such fake elements will only increase as we go along. Job postings have not been lucky enough to slip through the grip of this fake saga. Every day, thousands of Job requirements are posted and it is nearly impossible to manually check and understand which is fake and which isn't. On the other hand, it is also a very important issue to solve.

In this particular problem, I have tried to tackle the fake job posting issue with the help of classification techniques and NLP. The dataset has been taken from Kaggle and contributed to Kaggle by The University of the Aegean | Laboratory of Information & Communication Systems Security.

##**Context**<br><br>
This dataset contains 18K job descriptions out of which about 800 are fake. The data consists of both textual information and meta-information about the jobs. The dataset can be used to create classification models which can learn the job descriptions which are fraudulent.
The data is taken from [www.Kaggle.com](https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction)https://www.kaggle.com/datasets/shivamb/real-or-fake-fake-jobposting-prediction
## Column description:
* job_id: Unique job id for each posting
* title: Title of the job offered
* location: Geographical location of the job ad.
* department: Corporate department (e.g. sales).
* salary_range: Indicative salary range (e.g. $50,000-$60,000)
* company_profile: A brief company description.
* description: The details description of the job ad.
* requirements: Enlisted requirements for the job opening.
* benefits: Enlisted offered benefits by the employer.
* telecommuting: True for telecommuting positions.
* has_company_logo: True for the respective company having a logo.
* has_questions: True for having questions.
* employment_type: Type of employment(e.g. Full-time)
* required_experience: required experience(e.g. Mid-senior Level)
* required_education: required education to apply for the job(e.g. undergraduate)
* Industry: Industry of work(e.g. Computer Software)
* Function: Function to be performed in the job(e.g. Marketing)
* Fraudulent: Target Variable. It indicates if the job posting is fake or not.
