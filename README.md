# **Student Advisor Chatbot**

This repository contains the code and resources for the **Student Advisor Chatbot**, an AI-driven tool designed to provide personalized academic advice to students based on their performance data. It leverages **OpenAI's GPT models**, **LangChain**, and **Panel** to create an interactive chatbot that offers tailored advice depending on a student's overall academic performance and subject-specific scores.

## **Features**
- The chatbot uses **LangChain's** `AgentExecutor` and `ChatOpenAI` to deliver personalized feedback and academic guidance.
- Provides different types of advice based on the student's performance category (e.g., basic support for students scoring under 40%, advanced recommendations for high performers).
- Fetches student performance data from JSON files and dynamically adjusts advice based on scores.
- The chatbot interface is built with **Panel**, offering a simple and interactive chat experience.


## **Technologies Used**
- **LangChain**: To create a chain of prompts and manage tools for interacting with the student data.
- **OpenAI GPT API**: For generating responses and providing advice based on student performance.
- **Panel**: For creating a user-friendly dashboard to interact with the chatbot.
- **Python**: Main programming language used for logic and interaction.
- **JSON**: Data format for student information.

## **Contributing**
Feel free to open an issue or submit a pull request if you have suggestions or improvements for this project.

## **License**
This project is licensed under the **MIT License**.

## **Contact**
For any questions, feel free to reach out at:

- **Email**: karthikkckarthik02@gmail.com
- **LinkedIn**: [Karthik K C](https://www.linkedin.com/in/karthik-k-c-695540209/)



## **Project Structure**
```bash
.
├── student_advisor_chatbot.ipynb   # Main Jupyter notebook running the chatbot
├── student_advisor.py              # Python script version of the chatbot
├── student3.json                   # Example student data file (more in the same format)
├── student_data/                   # Folder containing multiple student JSON data files
├── requirements.txt                # Python dependencies for the project
├── README.md                       # Project documentation




