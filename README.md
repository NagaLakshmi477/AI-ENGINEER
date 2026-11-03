# AI Engineer — Ollama Installation

## 1. Install Ollama

Download Ollama for Windows:

https://ollama.com/download/windows

**Why?** To download and run AI models on our laptop.

## 2. Check Ollama Version

```cmd
ollama --version
```

**Why?** To verify that Ollama is installed correctly.

## 3. Download Llama 3.2

```cmd
ollama pull llama3.2
```

**Why?** To download the Llama 3.2 model to our laptop.

## 4. Run Gemma 3 270M

```cmd
ollama run gemma3:270m
```

**Why?** To run a small AI model locally and practice using prompts.

## 5. Run Phi-3

```cmd
ollama run phi3
```

**Why?** To try another AI model and compare its responses.

## 6. Run GPT-OSS

```cmd
ollama run gpt-oss

ollama run qwen2.5:7b
```

**Why?** To explore another AI model. Check its hardware requirements before downloading.

## 7. Check Downloaded Models

```cmd
ollama list
```

**Why?** To see which AI models are downloaded on our laptop.

---
## setting env with git and cursor

open powershell 
install git
close the powershell and repoen new and serach git command 
create a floder called projects
mkdir projects
cd projects
git clone https://github.com/ed-donner/llm_engineering.git
cd llm_engineering

download cursor
https://cursor.com/

open cursor and open ide
uv --version
uv self update
uv sync

we can a one file .env that stores all our secrets
