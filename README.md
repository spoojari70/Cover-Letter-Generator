# Job Application Assistant

This project is a Streamlit-based web application that helps users generate personalized cover letters for job applications by scraping job postings from provided URLs.

## Features

- Web scraping of job postings from career pages
- Extraction of job details including role, experience, skills, and description
- Generation of personalized cold emails for job applications
- Integration with a portfolio matching system

## Installation

To set up this project, follow these steps:

1. Clone the repository
2. Install the required dependencies:
   ```
   pip install streamlit langchain-groq langchain-core python-dotenv
   ```
3. Set up your environment variables:
   - Create a `.env` file in the project root
   - Add your Groq API key: `GROQ_API_KEY=your_api_key_here`

## Usage

To run the application:

1. Navigate to the project directory
2. Execute the following command:
   ```
   streamlit run main.py
   ```
3. Open the provided URL in your web browser
4. Enter the URL of a job posting page
5. Click "Submit" to generate a personalized cover letter

## Project Structure

- `main.py`: Contains the Streamlit app setup and main execution flow
- `chains.py`: Implements the `Chain` class for job extraction and email generation
- `utils.py`: Provides utility functions for text cleaning

## Dependencies

- Streamlit
- LangChain (Groq)
- python-dotenv

## Contributing

Contributions to improve the project are welcome. Please follow these steps:

1. Fork the repository
2. Create a new branch
3. Make your changes and commit them
4. Push to your fork and submit a pull request
