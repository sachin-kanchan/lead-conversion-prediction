# Lead Conversion Predictive Modeling for X Education

## Project Overview

This project aims to develop a predictive model to identify high-potential leads and improve the lead conversion rate for X Education, an online education company. The primary objective is to build a logistic regression model that can assign a Lead Score (between 0 and 100) to each lead based on their likelihood of conversion.

## Repository Contents

This repository contains the following files:

1. **Jupyter Notebook (EDA_and_ModelBuilding.ipynb)**: This notebook includes the complete process of data preprocessing, exploratory data analysis (EDA), feature engineering, and logistic regression model development.

2. **Project Summary (Project_Summary.docx)**: A word document providing a 500-word summary of the project, including the methodology, key findings, and recommendations.

3. **Stakeholder Questions (Stakeholder_Questions.docx)**: A word document addressing the four questions posed by the stakeholders.

4. **Presentation Slides (Presentation.pptx)**: A PowerPoint presentation summarizing the project, analysis, and key takeaways.

5. **README.md**: This file, which provides an overview of the project and the contents of the repository.

## Key Findings

1. The top three variables contributing most to lead conversion probability are:
   - Tags_Closed by Horizzon: 9.5875 
   - Tags_Lost to EINS: 7.7425  
   - Tags_Will revert after reading the email: 6.9136 

2. The top three categorical/dummy variables that should be focused on to increase the probability of lead conversion are:
   (Same as above)
   - Tags_Closed by Horizzon: 9.5875 
   - Tags_Lost to EINS: 7.7425  
   - Tags_Will revert after reading the email: 6.9136 

## Recommendations

1. **Aggressive Lead Conversion during Intern Period**:
   - Use the Lead Score (0-100) as a primary filtering mechanism
   - Focus exclusively on leads with scores above 60 (high conversion probability)
   - Prioritize leads with longer website visit times, multiple visits, and engagement from high-performing lead sources
   - Implement a rapid, personalized outreach approach for these top-scored leads
   - Train interns to use the predictive model as a key decision-making tool
   - Set up a structured follow-up process with multiple touchpoints for high-potential leads

2. **Minimizing Unnecessary Phone Calls**:
   - Use the Lead Score as a strict filtering mechanism, only contacting leads with scores above 60
   - Implement an automated communication system for lower-priority leads, reserving phone calls for those with extremely high conversion potential
   - Create a cost-benefit analysis framework to calculate the potential return on investment for each phone call
   - Develop a triage system that categorizes leads based on conversion probability, potential revenue, and resource investment required

For more details, please refer to the accompanying documents in this repository.
