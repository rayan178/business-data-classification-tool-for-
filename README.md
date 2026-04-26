Processes Excel files directly (.xlsx)
Automatically classifies product names into categories:
GROCERY
DRINKS
HOUSEHOLD
CONFECTIONERY
OTHER
Uses prompt-engineered rules for consistent classification
Skips already classified rows
Saves results incrementally to prevent data loss
Handles errors gracefully

client = OpenAI(api_key="YOUR_API_KEY")  ->  👉 Get your API key from [OpenAI](https://openai.com/?utm_source=chatgpt.com)

