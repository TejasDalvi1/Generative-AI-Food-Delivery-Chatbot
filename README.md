===============================================================================
# Generative-AI-Food-Delivery-Chatbot
===============================================================================

## Tech stack:
        (1)Python
        (2)Chainlit
        (3)OpenAI(gpt-3.5-turbo)        
-------------------------------------------------------------------------------
## Steps to run:

### (1) Create and activate Environment
```bash
conda create -n llmenv python=3.10 -y
```
```bash
conda activate llmenv
```

### (2) Install "requirements.txt"
```bash
pip install -r requirements.txt
```

### (3) Create a `.env` file in the root directory and add your OpenAI credentials:
```ini
OPENAI_API_KEY = "Put_Your_Key"
```

### (4) Initialize chainlit
```bash
chainlit init
```

### (5) Run "app.py"
```bash
chainlit run app.py
```

### (6) Click on the link got after step (5) and converse with chatbot:
```bash
open up localhost:
```