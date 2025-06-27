Nexus Gen AI is an LLM based system that converts natural language queries into SQL, allowing users to interact with databases without writing SQL Query. 

Objectives :
1. Automate SQL query generation using NLP.
2. Enable non-technical users to access databases easily.
3. Reduce manual SQL writing and technical dependency.
4. Improve data retrieval.

Methodology : The project uses a Streamlit-based web interface where users input natural language queries. LangChain and the Llama3 model (via ChatGroq) process the input and convert it into SQL commands. These commands are executed on connected SQLite or MySQL databases, and the results are displayed back to the user in real-time.
- Frontend: Streamlit web interface.
- NLP Engine: LangChain + Llama3 model (ChatGroq).
- Database: SQLite & MySQL.
- Process: Query → SQL → Database → Result → Display.

Result : Nexus Gen AI successfully translated natural language queries into accurate SQL statements with ~99% accuracy. The system responded within 2–4 seconds on average and worked efficiently across both SQLite and MySQL databases. Users could retrieve, filter, and analyze data without writing any SQL, making database access faster and more user-friendly.
- Accuracy: ~99% (as per testing)
- Response Time: 2–4 seconds/query.
- Works with simple & complex SQL queries.






