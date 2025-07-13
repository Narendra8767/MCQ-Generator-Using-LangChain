🚀 Built an AI-Powered MCQ Generator Using LangChain + OpenAI API<br>
I recently built a powerful tool that leverages the capabilities of LLMs and LangChain to automatically generate Multiple Choice Questions (MCQs) from any uploaded document — making content creation easier for educators, trainers, and exam designers. 📚🤖

![image alt](https://github.com/Narendra8767/MCQ-Generator-Using-LangChain/blob/9dc19eb26f69e395460bf370cde62efcc5e263f2/image/index.png)

![image](https://github.com/Narendra8767/MCQ-Generator-Using-LangChain/blob/9253cbbbbd14903012caa7a252a5d80fefc2abb4/image/result.png)

![image](https://github.com/Narendra8767/MCQ-Generator-Using-LangChain/blob/8758a7d8e212741605521ead747cb3ec4705bca2/image/workflow.png)


🛠️ Tech Stack:
LangChain – for prompt templating and OpenAI model interaction<br>
OpenAI GPT-4 API – for natural language generation<br>
Flask – to build the web interface<br>
pdfplumber, python-docx – for extracting text from PDFs and DOCX files<br>
FPDF – for generating downloadable PDF quiz files<br>


📈 Project Workflow:<br>
1️⃣ File Upload<br>
Users can upload .pdf, .docx, or .txt files through a simple web interface.<br>
2️⃣ Text Extraction<br>
The backend parses the document and extracts clean, structured text using file-type specific libraries.<br>
3️⃣ MCQ Generation (LLM + LangChain)<br>
A custom LangChain prompt is used to instruct GPT-4 to:<br>
Generate clear, relevant questions<br>
Provide four answer options<br>
Indicate the correct answer explicitly<br>
Users can choose how many questions to generate (num_questions input).<br>
4️⃣ Results Display + Export<br>
The MCQs are:<br>
Displayed on-screen for review<br>
Saved as .txt and .pdf for easy download<br>
Made accessible via a one-click download link<br>


📦 Docker Integration:<br>
To ensure easy deployment and platform independence, I containerized the entire MCQ Generator application using Docker. This allows anyone to run the project in seconds without worrying about environment setup or dependency issues.

✅ Benefits:<br>
One-command deployment<br>
Works across any OS with Docker<br>
No need to manually install Python libraries<br>
Ideal for demos, workshops, or classroom tools<br>

🐳 Public Docker Image:<br>
You can pull and run it directly from Docker Hub:<br>
🔗 https://hub.docker.com/repository/docker/narendratekale49/mcq-generator/general

