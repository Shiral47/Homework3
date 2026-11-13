# Project requirements and technical specifications

## Git and GitHub setup
- Connect local Git to GitHub account `Shiral47`; use GitHub CLI browser authentication and verify the signed-in account.
- Configure this project's commit identity as `Shir Alkalay` / `shiralklay2000@gmail.com`.
- Initialize this folder on branch `main`, create public repository `Homework3`, set it as `origin`, commit the project, and push `main` with upstream tracking.
- Never place passwords, authentication tokens, or OpenAI API keys in project files.

## Project files
- Create a beginner-friendly Google Colab notebook named `to-do app.ipynb` and `README.md` in a Git-tracked project repository.
- Create this `prompt.md` to document the requirements and technical specifications.

## Notebook behavior
- Include an OpenAI SDK installation step using `!pip -q install openai`.
- Securely request the OpenAI API key at runtime with `getpass`; do not hardcode, display, or store it in source code, notebook outputs, or Git/GitHub.
- Prompt for an everyday object using `input()`.
- Use `client.responses.create` with model `gpt-6-luna` to request exactly one unusual, creative, and practical use for that object.
- Keep Python simple and well-commented, arranged in clean Colab cells with explanatory Markdown.

## README content
- Briefly describe the project and repository structure.
- Explain how to clone/open the notebook from GitHub in Google Colab and run it.
- State that an OpenAI API key is required at runtime and explain safe key handling, including keeping it out of commits and GitHub repositories.

## Git record
- Record the completed setup and project artifacts in Git history with a commit, then publish the `main` branch with upstream tracking after authentication and account verification.
