# SQL-data-retrieval-Langchain-

## Project Summary: Chat with SQL using LLM Agent (OpenAI)

## Objective:
Develop a system that integrates an LLM (Large Language Model) agent with SQL databases, enabling users to interact with their databases using natural language queries.

### Key Components:

### Libraries and Tools:

- langchain: For managing the interaction between the LLM and SQL.
- openai: For utilizing OpenAI's GPT models.
- pymysql: For connecting to MySQL databases.
  
### Setup:

- Environment Setup:
Install necessary libraries: langchain, openai, pymysql.
Set up the OpenAI API key in the environment variables.
- Database Connection:
Connect to a MySQL database using SQLDatabase.from_uri.
- LLM Initialization:
Initialize the LLM model (gpt-3.5-turbo) using ChatOpenAI.
- Toolkit and Agent Executor:
Set up SQLDatabaseToolkit with the database and LLM.
Create an SQL agent using create_sql_agent.

### Functionality:

- The agent can execute SQL queries based on natural language input. Example queries include:
- Counting the number of tables in the database.
- Counting rows in a specific table.
- Querying specific data, such as counting animals of a certain color.

### Conclusion:
- This project demonstrates the integration of OpenAI's LLM with SQL databases, allowing users to perform database operations through natural language queries. The system is set up with necessary libraries, API keys, and database connections, enabling efficient data querying and visualization.
