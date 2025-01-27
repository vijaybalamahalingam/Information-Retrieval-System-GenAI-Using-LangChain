# Generative AI - Information Retrieval System Using LangChain and PaLM2

This repository contains an **Information Retrieval System** built using **LangChain** and **Generative AI (GenAI)** technologies. The system is designed to retrieve relevant information from a knowledge base or external documents using state-of-the-art natural language processing techniques. By leveraging LangChain's modular framework and the power of GenAI, this project enables efficient, context-aware information retrieval for a wide range of applications.

## Features

- **Contextual Search**: Retrieves information based on natural language queries.
- **Generative Responses**: Uses GenAI to provide detailed, human-like responses.
- **Document Parsing**: Processes and indexes unstructured documents for efficient search.
- **Integration with LangChain**: Utilizes LangChain to manage retrieval pipelines.
- **Extensibility**: Easily customizable for different datasets and domains.

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/vijaybalamahalingam/Information-Retrieval-System-GenAI-Using-LangChain.git
```
### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n llmapp python -y
```

```bash
conda activate llmapp
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your GOOGLE_API_KEY as follows:

```ini
GOOGLE_API_KEY= "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# Finally run the following command
streamlit run app.py
```

Now,
```bash
open up : http://localhost:8501
```


### Techstack Used:

- Python
- LangChain
- Streamlit 
- PaLM2
- FAISS