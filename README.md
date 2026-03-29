# ClaudeAPI

A small Python notebook project demonstrating how to call the Anthropic Claude API using the `anthropic` Python client and `.env` environment variables.

## Project contents

- `claudeapi.ipynb` - Jupyter notebook with the API client setup and example request flow
- `.gitignore` - ignores environment files, Python cache, virtual environments, Jupyter checkpoints, and editor files
- `.env` - local environment file for storing API keys and secrets (ignored by Git)

## Setup

1. Create a Python environment (optional but recommended):

   ```bash
   python -m venv venv
   .\venv\Scripts\activate
   ```

2. Install dependencies:

   ```bash
   pip install anthropic python-dotenv
   ```

3. Create a `.env` file in the project root with your Anthropic API key:

   ```text
   ANTHROPIC_API_KEY=your_api_key_here
   ```

## Usage

Open `claudeapi.ipynb` in Jupyter or VS Code and run the cells in order:

1. Install dependencies
2. Load environment variables
3. Initialize the Anthropic client
4. Send a prompt to Claude

## Notes

- Keep `.env` out of source control. It is already included in `.gitignore`.
- The notebook uses the `Anthropic` client from the `anthropic` package.
- Modify the prompt or model name inside the notebook to test different requests.
