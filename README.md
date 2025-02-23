# AI Debate: Steve Jobs vs. Elon Musk  

## Overview  
An AI-powered debate platform where AI versions of **Steve Jobs** and **Elon Musk** engage in a discussion on various technology-related topics. Both the bots are created using the Groq API with Meta's LLaMA 3.3-70B model, and responses are displayed dynamically using Streamlit. 

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/jobs-vs-musk-debate.git
   cd jobs-vs-musk-debate

2. Install dependencies:
    ```bash
    pip install streamlit python-dotenv

3. Create a .env file in the project directory and add the following line:
    ```bash
    GROQ_API_KEY=your_api_key_here

4. Navigate to the project directory and run the script using following command:
    ```bash
    streamlit run Debate.py
