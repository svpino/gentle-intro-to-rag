# A Gentle Introduction to RAG Applications

The [notebook](rag.ipynb) in this repository breaks down a simple RAG application to help you understand how every component works. It also comes with a video in which I walk you through the notebook step by step.

If you know a little bit of Python, you'll leave with a complete understanding of how you can use a basic RAG system to answer questions from a PDF document using an LLM.

To make things a bit more interesting, I'm using Llama 3.1 as the LLM that powers the system. Super cool to learn how to use open-source models and run them locally.

## Setup

Start by installing the required libraries in your virtual environment:

```bash
$ pip install --upgrade pip
$ pip install -r requirements.txt
```

We'll be using [Ollama](https://ollama.com/), so head over their site and install it. If you are running this in Linux, you can run the following commands to install Ollama and download Llama 3.1 8B.

```bash
$ curl -fsSL https://ollama.com/install.sh | sh
$ ollama run llama3.1
```

If you are not using Linux, head over the [Ollama](https://ollama.com/) website and follow the instructions for your operating system.


## Video
Here is a video with step by step instructions:

[![A gentle introduction to RAG using open-source models](https://img.youtube.com/vi/q9MD_hU2Yd8/0.jpg)](https://www.youtube.com/watch?v=q9MD_hU2Yd8)
