# DailyBites.Recipes
The core service responsible for generating and managing daily recipe suggestions in DailyBite. It takes user inputs such as language and cooking or ordering preference, queries the OpenAI API for results, stores them in a SQL database with unique keys to prevent duplicates, and ensures users can access or refresh their past 30-day recipe history.
