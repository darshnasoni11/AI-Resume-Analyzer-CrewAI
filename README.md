# AI Resume Analyzer using CrewAI

## Project Overview

AI Resume Analyzer is an AI-powered resume analysis project developed using Python and CrewAI. It uses multiple AI agents to analyze a candidate's resume, suggest improvements, and provide relevant job recommendations based on the target role and location.

## Features

- Extracts text from PDF and DOCX resumes.
- Analyzes resume sections and identifies strengths and weaknesses.
- Provides resume improvement suggestions.
- Evaluates ATS compatibility.
- Generates job recommendations based on the target role and location.
- Produces separate reports for resume feedback, resume improvement, and job recommendations.
- Packages generated reports into a ZIP file.

## Technologies Used

- Python
- CrewAI
- OpenAI API
- PyMuPDF
- python-docx
- Google Colab
- Serper API (optional, if configured)

## Multi-Agent Workflow

The project uses three AI agents:

1. **Resume Feedback Agent:** Analyzes the resume and identifies strengths, weaknesses, and areas for improvement.
2. **Professional Resume Advisor:** Suggests improvements to the resume's content, structure, and presentation.
3. **Job Advisor:** Recommends relevant job opportunities based on the candidate's target role and location.

## Project Requirements

- Python
- Google Colab or a compatible Python environment
- OpenAI API key
- Serper API key (if using web search)

## How to Run the Project

1. Open the project notebook in Google Colab.
2. Install the required libraries.
3. Configure your API keys securely using Colab Secrets or environment variables.
4. Upload your resume in PDF or DOCX format.
5. Enter your target job role and location.
6. Execute the notebook cells in order.
7. Review the generated resume feedback, improved resume suggestions, and job recommendations.
8. Download the ZIP file containing the generated reports.

## Project Output

The project generates three reports:

- `resume_feedback.md`
- `improved_resume.md`
- `job_recommendations.md`

These reports are packaged into a downloadable ZIP file.

## Project Structure

```text
AI-Resume-Analyzer-CrewAI/
│
├── AI_Resume_Analyzer.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Future Enhancements

- Interactive web application.
- Resume comparison with job descriptions.
- Advanced ATS keyword matching.
- More detailed job matching and recommendation features.
- Support for additional resume formats.

## Author

**Darshna Sonar**

B.Tech – Artificial Intelligence and Data Science

GitHub: https://github.com/darshnasoni11

---

*This project was developed as an AI-powered resume analysis and career assistance application using CrewAI.*