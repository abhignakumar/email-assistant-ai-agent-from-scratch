# Email Assistant ReAct AI Agent from Scratch (Google Gemini SDK)

## Overview

- Built a fully functional autonomous AI agent from scratch using the **ReAct (Reasoning + Acting)** architecture, designed to simulate real-world decision-making and tool usage.
- [Google Colab Link](https://colab.research.google.com/drive/1MBKRyTpIMFe4U-DhaBWsq7Pxh7M3nEOk?usp=sharing)

## Key Highlights

- Integrated **Google Gemini (gemini-2.5-flash LLM model)** via the **genai SDK** to dynamically generate multi-step reasoning and invoke tool-based actions in response to user queries.
- Engineered two custom tools:
  - **find email:** Retrieve a user’s email from a remote **SQL database** using only their first name.
  - **send email:** Compose and send dynamic emails by inferring appropriate subject and body from the given prompt.
- Demonstrated structured action formats and **JSON-based tool usage** within LLM-generated responses.
- Built a second version leveraging **Gemini’s built-in Function Calling API** for direct, structured tool execution, simplifying the reasoning loop.
- Positioned the project as a **foundation for building intelligent agents** with extensible tools for SaaS workflows or autonomous copilots.

## Tech Stack

- **Language:** Python
- **AI Model:** Google Gemini (gemini-2.5-flash)
- **SDK:** genai SDK (Google Gemini)
- **Tools:** SQL Database (for custom email lookup)
