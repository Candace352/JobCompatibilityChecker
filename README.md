# Project Title
Job Compatibility Checker

# Project Description
This project builds an application that allows a user to upload a job description file and resumes in pdf format only. The application then outputs a percentage similarity, indicating how well the resume fits the job description and also gives a ranking on which resumes are better aligned with the job description given. This project makes use of the following tools:

Generative Pre-trained Transformer 4 Turbo(GPT4-turbo) is a type of language model that uses deep learning that can accept text files, check and calculate similarities and output the results with clear explanations based on the prompt defined within the code. To make use of the GPT4 turbo, we had to purchase the secret key on the OpenAi website.

LangChain, which allowed for connecting the GPT4 to our sources of information(the resumes and job description) to help create the transformative application.

Streamlit is an open-source framework that allows us to design and deploy our application.

# API Reference
It utilizes OpenAI's GPT-4 turbo for natural language understanding and employs

get_completion(prompt, model="gpt-4-1106-preview")

Description: Sends a prompt to the OpenAI GPT-4 model for completion.

Input: prompt (str): The prompt to be completed. Model (str, optional): The OpenAI GPT-4 model to use. The default is "gpt-4-1106-preview".

Output: A completed response was generated by the GPT-4 model.

# Deployment
To deploy this application successfully, you have to install the following libraries in your environment:

openai

streamlit

langchain

-- Steps

1. Clone the repo from the GitHub repository
2. Install the necessary libraries
3. Run the command streamlit run projectCode.py
4. Link to deployed application:
