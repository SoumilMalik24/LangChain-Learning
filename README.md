# LangChain Learning Journey

A comprehensive collection of Jupyter notebooks documenting a step-by-step learning path into **LangChain**, **Generative AI**, and **Agentic Workflows**. This repository covers foundational concepts, tool usage, and advanced agent architectures.

## Repository Structure

The project is organized into sequential modules, progressing from basic chains to complex multi-tool agents.

| File | Description |
| --- | --- |
| **`1-LangChain-Intro.ipynb`** | Introduction to LangChain syntax, basic chains, and model interaction. |
| **`2-Tools.ipynb`** | Creating and integrating custom tools (functions) for LLMs to use. |
| **`3-Agents-Intro.ipynb`** | Foundations of Agentic AI—enabling models to reason and act. |
| **`4-Multi-Tool-Agent.ipynb`** | Building advanced agents capable of selecting from multiple distinct tools. |
| **`5-Messages.ipynb`** | Managing chat history, prompt templates, and message roles (System/User/AI). |
| **`6-Structured-Output.ipynb`** | Techniques for forcing LLMs to return structured data (JSON/Pydantic). |
| **`7.Middleware.ipynb`** | Advanced handling of chain execution, interception, or custom processing layers. |

## Tech Stack

* **Python**: Core programming language.
* **LangChain**: Framework for developing applications powered by language models.
* **Jupyter Notebooks**: Interactive coding environment.
* **uv**: Blazing fast Python package installer and resolver.

## Getting Started

This project uses **[uv](https://github.com/astral-sh/uv)** for dependency management, ensuring fast and reliable builds.

### Prerequisites

* Python 3.10+
* An API Key (e.g., OpenAI `OPENAI_API_KEY` or Anthropic `ANTHROPIC_API_KEY`) stored in a `.env` file.

### Installation

1. **Clone the repository:**
```bash
git clone https://github.com/SoumilMalik24/LangChain-Learning.git
cd LangChain-Learning

```


2. **Install dependencies using uv:**
If you don't have `uv` installed, get it first:
```bash
pip install uv

```


Then, sync the project dependencies:
```bash
uv sync

```


*(Alternatively, if you prefer standard pip)*:
```bash
pip install -r requirements.txt

```


3. **Set up Environment Variables:**
Create a `.env` file in the root directory and add your API keys:
```env
OPENAI_API_KEY=sk-...
# Add other keys as required by specific notebooks

```


4. **Run the Notebooks:**
You can launch Jupyter directly or via `uv` if configured:
```bash
jupyter notebook

```



## Key Concepts Covered

* **Chains vs. Agents:** Understanding when to use a hard-coded sequence of steps vs. a reasoning engine.
* **Tool Calling:** equipping LLMs with capabilities to search the web, calculate math, or access APIs.
* **Structured Output:** Moving beyond text generation to generate reliable code and data structures.
* **State & Memory:** Managing conversation context over time.

## Author

**Soumil Malik**

[GitHub Profile](https://github.com/SoumilMalik24)

