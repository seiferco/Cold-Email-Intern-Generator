# Cold Email Intern Generator

## Overview

The **Cold Email Intern Generator** is an AI-powered tool designed to help students and professionals streamline the process of writing personalized cold emails for internship applications. By leveraging automation and natural language processing (NLP), this tool matches your skills and projects to job descriptions, enabling you to efficiently craft tailored emails that stand out.

## Features

- **Dynamic Personalization**: Automatically matches your portfolio projects to the job requirements for maximum relevance.
- **AI-Enhanced Text Generation**: Uses NLP to draft professional and grammatically sound emails.
- **CSV Integration**: Reads your project details from a CSV file and incorporates them into emails.
- **Batch Processing**: Generates personalized emails for multiple job applications simultaneously.
- **Error Reduction**: Includes AI-powered grammar and spell-checking for polished content.

## Requirements

- Python 3.8+
- Libraries:
  - pandas
  - streamlit
  - os
  - langchain
  - langchain_groq
  - langchain_core
  - dotenv
  - chromadb
  - uuid
  - re

Install dependencies using:

pip install -r requirements.txt

## Setup

1. Clone the repository:

git clone https://github.com/seiferco/Cold-Email-Job-Creator.git cd Cold-Email-Intern-Generator

2. Prepare your data:
- Create a `my_projects.csv` file in the `/resources` folder.
- The file should contain columns such as Project Name, Description, Technologies, and Impact.

3. Run the application:

streamlit run app/main.py

## Usage

1. **Load Portfolio Data**:
- Upload your `my_projects.csv` file to the app.
- Ensure it contains all the projects and skills you want to showcase.

2. **Enter Job Details**:
- Provide the job title, company name, and job description.

3. **Generate Emails**:
- The tool will create a customized email for the job.
- Review and fine-tune the draft before sending.

4. **Export Emails**:
- Save the generated emails to a file or copy them directly for use.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
