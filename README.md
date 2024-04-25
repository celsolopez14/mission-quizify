# Gemini-Quizify
## Overview
Gemini-Quizify is an AI-Generated Quiz Tool project that focuses on providing students and learners with accessible and effective means to reinforce their understanding of various topics. Leveraging AI technology, the tool dynamically generates quizzes based on user-provided documents, offering instant feedback and detailed explanations to facilitate deeper comprehension and retention of knowledge, ultimately enhancing the learning experience.

## Installation
### Prerequisites
To run Gemini Quizify, ensure that the following prerequisites are met:
 - Python 3.6 or higher
 - AI Platform
 - Streamlit
 - Google Cloud SDK

Include these prerequisites in your installation instructions to ensure that users have everything they need to run your project successfully.

### Step-by-Step Installation Guide
1. Clone the repository
    Start by cloning the repository to your local machine. Use the following command:
```bash
git clone https://github.com/celsolopez14/mission-quizify.git
cd mission-quizify
```

2. Set Up a Virtual Environment (Optional)
It's a good practice to create virtual environment when working with Python projects. This keeps your projects dependencies isolated. If you have virtualenv install create a new environment with:
```bash
virtualenv env
source venv/bin/activate
```

3. Install Dependencies
Inside the virtual environment, install all the dependencies necessary by running:
```bash
pip install -r requirements.txt
```

4. Google Cloud Auth
To be able to use the google cloud services, you first need to auth with your google cloud credentials. You can do this by running either of the following commands:
```bash
gcloud init
gcloud auth application-default login
```
5. Authentication json file (Optional)
The project sets the Google credentials by accessing the authentication.json file obtained from your google cloud services. You can declare your credentials however you like, but just know that if you pass your json file into the mission-quizify directory you can skip this part.

### Starting Gemini Quizify App
After the installation, you can start the Gemini Explorer App by simply running the python file. Navigate to the project directory and run:
```bash
cd tasks
cd task_10
streamlit run task_10.py
```

After running the previous command, the app will show you the Local URL on the terminal, if it does not open automatically on your browser. Now you can enjoy the AI-Generated Quiz Tool app!



