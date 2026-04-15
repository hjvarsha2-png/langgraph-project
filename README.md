# LangGraph Projects & Workflows

This repository contains a collection of Jupyter Notebooks demonstrating various AI workflows and agents built using LangGraph and LangChain.

## Contents

- **`batman.ipynb`**: Demonstrates a data manipulation and scoring workflow using a custom `BatsmanState`.
- **`7_review_reply_workflow.ipynb`**: An automated review reply agent that analyzes sentiment, diagnoses negative feedback, and drafts customized responses.
- **`8_X_post_generator.ipynb`**: Workflow that likely generates social media posts (X/Twitter).
- **`quadratic_equation_workflow.ipynb`**: A logical workflow handling quadratic equations.
- **`promtchaing.ipynb` & `prompt.ipynb`**: Experiments with prompt chaining and LLM instruction strategies.
- **`multill.ipynb` & `lg.ipynb`**: Additional LangGraph and LLM experimental workflows.

## Prerequisites

To run these notebooks, you will need to set up a virtual environment and configure your API keys.

1. Create a `.env` file in the root directory (make sure it's ignored in version control).
2. Add your required API keys (e.g., Mistral, OpenAI) to the `.env` file.
3. Install the necessary dependencies (like `langgraph`, `langchain`, etc.).

## Note
Ensure your `.env` file is added to a `.gitignore` file before pushing any updates to a public repository to keep your API keys secure!
