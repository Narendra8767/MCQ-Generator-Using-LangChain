🚀 Built an AI-Powered MCQ Generator Using LangChain + OpenAI API
I recently built a powerful tool that leverages the capabilities of LLMs and LangChain to automatically generate Multiple Choice Questions (MCQs) from any uploaded document — making content creation easier for educators, trainers, and exam designers. 📚🤖


🛠️ Tech Stack:
LangChain – for prompt templating and OpenAI model interaction

OpenAI GPT-4 API – for natural language generation

Flask – to build the web interface

pdfplumber, python-docx – for extracting text from PDFs and DOCX files

FPDF – for generating downloadable PDF quiz files


📈 Project Workflow:
1️⃣ File Upload
Users can upload .pdf, .docx, or .txt files through a simple web interface.

2️⃣ Text Extraction
The backend parses the document and extracts clean, structured text using file-type specific libraries.

3️⃣ MCQ Generation (LLM + LangChain)
A custom LangChain prompt is used to instruct GPT-4 to:

Generate clear, relevant questions

Provide four answer options

Indicate the correct answer explicitly

Users can choose how many questions to generate (num_questions input).

4️⃣ Results Display + Export
The MCQs are:

Displayed on-screen for review

Saved as .txt and .pdf for easy download

Made accessible via a one-click download link

📦 Docker Integration:
To ensure easy deployment and platform independence, I containerized the entire MCQ Generator application using Docker. This allows anyone to run the project in seconds without worrying about environment setup or dependency issues.

✅ Benefits:

One-command deployment

Works across any OS with Docker

No need to manually install Python libraries

Ideal for demos, workshops, or classroom tools

🐳 Public Docker Image:
You can pull and run it directly from Docker Hub:

🔗 https://hub.docker.com/repository/docker/narendratekale49/mcq-generator/general

