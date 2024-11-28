##how to install dependencies
1. create new project with python 3.10 or above
2. create new files "app.py" and "requirements.txt"
3. copy paste the code and the dependencies in both files respectively
4. install dependencies by running the following code in the terminal "pip install -r requirements.txt"
5. wait and let the skeletons update
6. onces done run streamlit "streamlit run app.py"
-------- onces you have got to this point, rest we will continue in the workshop
7. replace the api key and project key with your own
8. import the project into your action table



## Recruitment Helper - Your AI Assistant for Job Matching

This is a simple web app designed to help match job seekers with job descriptions, using AI to analyze CVs and extract useful insights. The app is built using Streamlit, making it easy to use with a friendly user interface.

### How It Works

- **Upload Your CV**: You start by uploading a PDF version of your CV.
- **Enter Job Description**: Then, you provide a job description for the role you are interested in.
- **AI Processing**: Once you hit the "Process Input" button, the AI analyzes your CV alongside the job description and provides a summary, rating, work experience details, and a skills match analysis.
- **Download Report**: You can also download a detailed report with all the findings in a convenient Word document format.

### Features

- **CV Analysis**: Extracts and processes the text from your uploaded CV.
- **Job Match Insights**: Compares your skills and experience to the job description and highlights matching skills, skills that don't match, and an overall rating.
- **Downloadable Report**: Generates a final report that you can download for your own records or to share with potential employers.

### Technology Stack

- **Streamlit**: For the web interface.
- **PyPDF2**: To extract text from PDF files.
- **JamAI API**: To analyze and generate job matching insights.
- **Python-docx**: To create a downloadable report.

This tool is ideal for anyone looking to quickly understand how well their skills match a particular job and to get AI-powered insights into improving their job application materials.

