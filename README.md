# Creative Everyday Object Ideas

A beginner-friendly Google Colab notebook that asks for an everyday object and uses the OpenAI Responses API to suggest one unusual, creative, practical use for it.

## Repository structure

- `to-do app.ipynb` — the Colab notebook with setup, secure API-key entry, and idea generation.
- `README.md` — project overview and instructions.
- `prompt.md` — project requirements and technical specifications.

## Open and run in Google Colab

1. Clone the repository with `git clone https://github.com/Shiral47/Homework3.git` (or download it from GitHub).
2. Open the notebook from the repository in Google Colab: [Open `to-do app.ipynb` in Colab](https://colab.research.google.com/github/Shiral47/Homework3/blob/main/to-do%20app.ipynb).
3. In Colab, run the notebook cells from top to bottom. When prompted, enter an everyday object.

An OpenAI API key is required at runtime. The notebook asks for it using Python's `getpass` so it is not echoed as you type. Keep the key private: never hardcode it in the notebook, include it in outputs, commit it, or upload it to a GitHub repository. If a key is ever exposed, revoke it and create a new one.
