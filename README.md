# AI Resume Analyzer Web Application

## Overview
The AI Resume Analyzer is a web application designed to automate the resume screening process using Artificial Intelligence (AI). The application leverages named entity recognition (NER) techniques to extract key information from resumes such as the user's name, email, phone number, and skills. It also offers suggestions for missing skills, provides resume scores, and recommends video tutorials to help improve resume writing.

## Features
- **Resume Upload**: Users can upload their resumes for analysis.
- **Resume Parsing**: The AI analyzes resumes, extracting details such as name, contact info, and skills.
- **Skill Suggestions**: The application highlights missing skills and suggests additional skills to include based on job market trends.
- **Resume Score**: An overall score is provided to assess the quality of the resume.
- **User Dashboard**: Users can view their analysis results and receive recommendations.
- **Admin Dashboard**: Admins can view all uploaded resumes and analyze candidate data.
- **Database Integration**: All resume data is stored in an SQL database for easy access and management.

## Technologies Used
- **Frontend**: HTML, CSS, JavaScript, React
- **Backend**: Python, streamlit, Named Entity Recognition (NER) Libraries
- **Database**: MySQL, PostgreSQL, or SQLite
- **Others**: RESTful API, Resume parsing libraries

## Setup Instructions

### 1. Install Dependencies

First, ensure you have the required libraries installed. Run the following commands to install the necessary libraries:

```bash
pip install -r requirements.txt
pip install nltk
pip install spacy==2.3.5
pip install https://github.com/explosion/spacy-models/releases/download/en_core_web_sm-2.3.1/en_core_web_sm-2.3.1.tar.gz
pip install pyresparser
