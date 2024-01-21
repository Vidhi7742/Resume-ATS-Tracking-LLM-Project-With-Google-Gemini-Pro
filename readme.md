# Resume ATS Tracking LLM Project with Google Gemini Pro

## Overview

This project is a Resume ATS (Application Tracking System) implemented using Google's Gemini Pro API. It evaluates resumes based on a given job description, providing a percentage match and highlighting missing keywords. The application is built using Streamlit for the user interface.

## Getting Started

## Prerequisites

Make sure you have the required dependencies installed by running:

```bash
pip install -r requirements.txt
```

## Configuration
Create a .env file in the project root with your Google API key:

GOOGLE_API_KEY="your_api_key_here"

## Usage
1. Run the Streamlit app:

```bash
streamlit run your_app_filename.py
```

2. Paste the job description and upload your resume in PDF format.

3. Click the "Submit" button to get the ATS evaluation.

## Project Structure

1. app.py: Main application file with the Streamlit app.
2. requirements.txt: List of project dependencies.
3. .env: Configuration file for environment variables.

Google Gemini Pro API
The project utilizes the Google Gemini Pro API for generative content generation. Make sure to obtain an API key and set it in the .env file.

## Contributions
Contributions are welcome! If you find any issues or have improvements, feel free to open an issue or submit a pull request.



