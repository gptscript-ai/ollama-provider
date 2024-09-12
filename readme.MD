# Ollama Provider

Assumes you have ollama running already, with the model you want to use configured.

## Usage

```
gptscript --default-model='llama3.1 from github.com/gptscript-ai/ollama-provider' examples/bob.gpt
```

## Development

Run using the following commands

```
python -m venv .venv
source ./.venv/bin/activate
pip install -r requirements.txt
DEBUG=true ./run.sh
```

```
gptscript --default-model='llama3.1 from http://127.0.0.1:8000/v1' examples/bob.gpt
```
