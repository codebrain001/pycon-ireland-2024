# Project Setup Instructions


## Prerequisites
- Python 3.10 or greater: [Download Python](python.org/downloads)
- Docker Desktop [Download Docker Desktop](https://www.docker.com/products/docker-desktop/)

## Clone the Repository
Clone the repository to a directory of your choosing:

- HTTPS:
```
git clone https://github.com/codebrain001/pycon-2024.git
```

- SSH:
```
git clone git@github.com:codebrain001/pycon-2024.git
```

- GitHub CLI:
```
gh repo clone codebrain001/pycon-2024
```

## Obtain API Keys
Get the following API keys for the project:

#### 1.  OpenAI API Key
- OpenAI models are the LLMs used for this project.
- Obtain your API key: [Where do I find my OpenAI API key?](https://help.openai.com/en/articles/4936850-where-do-i-find-my-openai-api-key)
- Note: Requires payment or use the test API with limited credit for demo purposes. 


#### 2. Serper Dev API Key
- For Google search functionality (first 2,500 search queries are free).
- Get your API key: [Get Serper Dev API key](https://serper.dev/api-key)

#### 3. Groq API Key
- Utilizing GROQ faster inference to some open source models
- Obtain your API key: [Get Groq API Key](https://console.groq.com/keys)

#### 4. Perplexity AI API Key
- Perplexity is a free AI-powered answer engine that provides accurate, trusted, and real-time answers to any question.
- For more advanced searching.
- It is paid to get and use its API.
- Get your API key: [Getting Started with Perplexity API](https://docs.perplexity.ai/guides/getting-started)

## Setup Virtual Environment
With the repository cloned on your system.

####  Create and activate a Python Virtual Environment
- macOS and Linux
```
 python3 -m venv pycon-ireland-env
source pycon-ireland-env/bin/activate
```
- Windows
```
python -m venv pycon-ireland-env
pycon-ireland-env\Scripts\activate
```

#### Install packages

Install the packages listed in requirements.txt:
```
pip install -r requirements.txt
```

## Load jupyter lab

```
jupyter lab
```