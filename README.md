# MedBot
Welcome to the **MedBot Project**! This chatbot is designed to assist users by providing medical information sourced from reliable books and references. It can help answer a variety of medical questions and provide helpful information.

## Features

- **Medical Information Assistance**: The chatbot provides answers to various medical questions.
- **Easy-to-Use Interface**: User-friendly chatbot interface to ask questions and receive medical guidance.
- **Comprehensive Knowledge Base**: The bot uses a curated knowledge base of medical books and trusted resources.
- **Instant Responses**: Get quick and accurate responses to your medical queries.

# How to run?
### STEPS:

Clone the repository

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 02- install the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone & openai credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GOOGLE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


```bash
# run the following command to store embeddings to pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

Now,
```bash
open up localhost:
```


### Techstack Used:

- Python
- LangChain
- Flask
- GPT
- Pinecone
