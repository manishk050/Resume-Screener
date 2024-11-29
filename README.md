
# Resume Screener

## Project Overview

This repository contains a machine learning project designed to automate resume screening. The goal is to streamline the recruitment process by quickly identifying the most suitable candidates based on customizable criteria.

## Dataset Description

The project uses resumes and job descriptions as input, focusing on:

- **Resume Parsing**: Extracting relevant details such as skills, experience, and qualifications.
- **Job Description Analysis**: Identifying key requirements to match against resumes.
- **Screening Output**: Ranked candidates based on skill matching and criteria.

## Key Features

- **Automated Resume Parsing**: Extract essential information from resumes in PDF or DOCX format.
- **Customizable Criteria**: Tailor screening parameters to match specific job requirements.
- **Machine Learning Integration**: Use algorithms for keyword matching and scoring.
- **Candidate Ranking**: Generate a ranked list of suitable candidates.

## Tools Used

- **Python**: For resume parsing, data analysis, and machine learning.
- **Libraries**:
  - `spacy`: For natural language processing.
  - `pandas`: For data manipulation.
  - `scikit-learn`: For model implementation.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/resume-screener.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the application:
   ```bash
   python app.py
   ```
4. Upload resumes and set criteria for screening.

## License

This project is licensed under the MIT License.
