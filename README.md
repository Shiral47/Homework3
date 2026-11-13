# TaskNest Support Ticket Router

A beginner-friendly Google Colab notebook that uses LangGraph to classify TaskNest customer support tickets and route each ticket to the appropriate team. An LLM selects the category; simple Python team nodes return fixed confirmation replies.

## Repository structure

- `TaskNest Ticket Routing.ipynb` — ticket classification, conditional routing, and graph visualization.
- `to-do app.ipynb` — an OpenAI Responses API notebook for creative everyday object ideas.
- `prompt.md` — project requirements and technical specifications.
- `README.md` — project overview and run instructions.

## Run the TaskNest notebook in Google Colab

1. Clone this repository with `git clone https://github.com/Shiral47/Homework3.git` or open its GitHub page.
2. Open [TaskNest Ticket Routing in Colab](https://colab.research.google.com/github/Shiral47/Homework3/blob/main/TaskNest%20Ticket%20Routing.ipynb).
3. In Colab, add an `OPENAI_API_KEY` secret and allow the notebook to access it.
4. Run the cells from top to bottom. The final cell includes a sample billing ticket. Replace its text with another ticket to see how the workflow routes it and what confirmation reply it returns.

The TaskNest notebook reads the OpenAI API key from Colab Secrets at runtime. Never hardcode a key, display it in outputs, commit it, or upload it to a GitHub repository. Keep secrets private and revoke any key that becomes exposed.

## Run the everyday object notebook

Open [to-do app in Colab](https://colab.research.google.com/github/Shiral47/Homework3/blob/main/to-do%20app.ipynb), run the cells in order, and enter an object when prompted. This notebook asks for an OpenAI API key at runtime using `getpass`; keep it out of saved outputs, source code, commits, and GitHub.
