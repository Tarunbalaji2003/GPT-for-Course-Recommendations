
# GPT-for-Course-Recommendations

This is an end to end LLM project based on Google Palm and Langchain.

## Project Highlights

- Use a real CSV file of FAQs . 
- Their human staff will use this file to assist their course learners.
- We will build an LLM based question and answer system that can reduce the workload of their human staff.
- Students should be able to use this system to ask questions directly and get answers within seconds

## You will learn following,
  - Langchain + Google Palm: LLM based Q&A
  - Streamlit: UI
  - Huggingface instructor embeddings: Text embeddings
  - FAISS: Vector database

## Installation

1.Clone this repository to your local machine using:

```bash
  git clone https://github.com/Tarunbalaji2003/GPT-for-Course-Recommendations.git
```
2.Navigate to the project directory:

```bash
  cd GPT-for-Course-Recommendations
```
3. Install the required dependencies using pip:

```bash
  pip install -r requirements.txt
```
4.Acquire an api key through makersuite.google.com and put it in .env file

```bash
  GOOGLE_API_KEY="your_api_key_here"
```
## Usage

1. Run the Streamlit app by executing:
```bash
streamlit run main.py

```

2.The web app will open in your browser.

- Click on create Knowledge base and wait for the while it take some time to create it. Now you are ready to give the prompts based on that you will recive the output.


## Sample Questions

 - How can I learn machine learning course
 - How to learn javascript

## Project Structure

- main.py: The main Streamlit application script.
- langchain_helper.py: This has all the langchain code
- requirements.txt: A list of required Python packages for the project.
- .env: Configuration file for storing your Google API key.
