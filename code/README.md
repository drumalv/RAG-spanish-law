# Readme

### Installation venv notebook

```bash
python3.11 -m venv .venv
source .venv/bin/activate
pip install -r code/requirements.txt
```

## Streamlit app

### Insllation venv

```bash
python3.11 -m venv .venv_streamlit
source .venv_streamlit/bin/activate
pip install -r code/app/requirements.txt
```
### Requirements

.ven in code folder with:

```
export AZURE_OPENAI_ENDPOINT=
export AZURE_OPENAI_API_KEY=
export OPENAI_API_VERSION=
export AZURE_GPT4TURBO_DEPLOYMENT=
export AZURE_GPT3TURBO_DEPLOYMENT=
export AZURE_ADA2_DEPLOYMENT=
```
### Exec streamlit

```bash
cd tfm
streamlit run code/app/main.py --server.port 8051
```
