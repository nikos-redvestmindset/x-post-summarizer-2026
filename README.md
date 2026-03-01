# x-post-summarizer-2026

This repository summarizes a public figure's 2026 X posts using AI.

## Project Description
This project analyzes and summarizes the 2026 X posts of a public figure, specifically the account handle @llm_wizard. The summary is generated using AI techniques.

## How It Was Built
The project was built using a LangGraph agent combined with GitHub MCP tools for repository operations and the X API v2 for retrieving posts.

## Replicating the Process
To replicate this process, follow these steps:

1. Obtain an X API Bearer Token by creating a developer account on X and generating the token.
2. Set the Bearer Token as an environment variable in your system:

   ```bash
   export X_BEARER_TOKEN='your_token_here'
   ```

3. Install the required Python dependencies:

   ```bash
   pip install requests
   ```

4. Use the provided `x_search.py` script to fetch recent posts from the desired X account.

5. Generate summaries based on the retrieved posts using AI tools or your preferred method.

Feel free to explore and modify the repository to suit your needs.
