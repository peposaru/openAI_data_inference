# AWS OpenAI Data Filler

This program retrieves rows from a PostgreSQL database, sends them to the OpenAI API for data inference, and updates the database with the results.

## Features

- Connects to PostgreSQL using user-provided credentials.
- Processes data row by row for inference via the OpenAI API.
- Logs activity with adjustable verbosity.
