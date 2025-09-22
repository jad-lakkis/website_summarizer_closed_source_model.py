# Website Summarizer

This is a simple Python script that summarizes the contents of any webpage using **OpenAI models**.

## Features
- Fetches a webpage and extracts only the main readable text (ignores scripts, styles, images, etc.).
- Sends the extracted content to OpenAI (`gpt-4o-mini`) for a clean markdown summary.
- Handles invalid websites and API errors gracefully.

## Requirements
- Python 3.9+
- OpenAI API key!

## Setup
1. Clone this repository.
2. Install dependencies:
   ```bash
   pip install openai python-dotenv requests beautifulsoup4
