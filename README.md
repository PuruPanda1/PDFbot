Steps to use Rag functionality in the Project.

PreRerquisite: Ollama Server (with mistral LLM downloaded) should be running in the background to load the LLM

1. Copy the PDF files in the data folder
2. using the terminal, setup the python environment and install packages inside requirements.txt
3. open terminal run command "python ingest.py" to create vector database
4. After Succesfull Creation of db, use command "chainlit run .\main.py" to run the server
5. Open "localhost:portNumber" in the browser | portNumber is given in the terminal
6. Now you can ask questions to the chatbot
