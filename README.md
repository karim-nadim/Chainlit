# Chatbot Implementation Using Chainlit

### - Chainlit is an open-source Python package, which allows to build production ready Conversational AI.

## How to run?


1. Create the conda environment
```bash
conda create -n newenv python=3.10 -y
```

2. Activate the environment
```bash
conda activate newenv
```

3. Install the required packages
```bash
pip install -r requirements.txt
```

4. Create .env file and add your OPENAI api key
```python
OPENAI_API_KEY = ""
```

5. Create a system prompt in a prompt.py file

6. Initialize the OPENAI client in llm.py

## Chainlit Commands
```bash
chainlit init
```

```bash
chainlit run app.py
```