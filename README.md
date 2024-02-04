
# Covid19 Chatbot

## Project Overview
This project is a chatbot developed using Streamlit, designed to provide information on Covid19. It leverages the OpenAI API to generate responses to user queries related to Covid19, including statistics, precautions, and general information.

## Getting Started

### Prerequisites
- Python 3.6 or higher
- pip

### Installation

1. Clone the repository:
   ```
   git clone [your-repository-url]
   ```
2. Navigate to the project directory:
   ```
   cd [project-directory]
   ```
3. Install required packages:
   ```
   pip install -r requirements.txt
   ```

### Running the Application

1. Before running the application, create a `st.secrets` file in the root directory of the project with your OpenAI API key:
   ```json
   {
     "openai_secret_key": "your_openai_api_key_here"
   }
   ```
   This file is necessary for the application to authenticate with OpenAI's API.

2. **Covid-19 Workplace Safety Plan**: Download the "2022-covid-19-workplace-safety-plan.pdf" from the following URL and store it in a folder named "data" under the root directory of your project.
   - Download URL: [2022-covid-19-workplace-safety-plan.pdf](https://www.dol.gov/sites/dolgov/files/general/plans/2022-covid-19-workplace-safety-plan.pdf)

3. To run the application, use the following command:
   ```
   streamlit run covid19_chatbot.py
   ```

## Acknowledgments
- OpenAI for the API
- Streamlit for the web application framework
