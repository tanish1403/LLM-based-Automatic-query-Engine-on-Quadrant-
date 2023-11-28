<h1 align="center">LLM based query project on Quadrant:</h1>
## Demo images
<br /><br />

![Demo working](demo.jpg)

<br /><br />
## Follow the steps
```bash
git clone "your git link"
```
```bash
pip install -r requirements.txt
```
## Update the API keys inside database_query.py
openai.api_key = 'your_openai_api_key'
qdrant_api_key = 'your_qdrant_api_key'
cohere_api_key = 'your_cohere_api_key'


```bash
python database_query.py
```