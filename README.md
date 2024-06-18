# Objective: 
Develop a Python application to extract key information from invoices using machine 
learning. The project involves training a model, optimizing it for deployment, and running it on a 
client desktop. The solution should handle various invoice formats in English, Dutch, and French 
without hardcoded labels, understanding the context to accurately extract information.

## steps to run:
-download a zip file of this repository.
-Open vscode, locate the project directory.
-open vision.py, run terminal with command: *!pip install streamlit google-generativeai python-dotenv langchain PyPDF2 chromadb faiss-cpu*
-In order to run this project you should have your API key from google's AI studio.
-make a .env file and write *GOOGLE_API_KEY=your_api_key_here*
-run *!npm install localtunnel* to install localtunnel 
-run *!streamlit run app.py &>/content/logs.txt &*
-and then, *!npx localtunnel --port 8501 & curl ipv4.icanhazip.com*
-paste the password which appeared after running above command, It may look something like *34.106.178.215* this.
