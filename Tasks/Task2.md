# Task 2: Data Intelligence Engine

## Objective
Develop a system that interprets user queries and returns accurate, structured responses based on controlled and predefined data sources.



## Problem Statement

Users may ask questions such as:
- "What is my progress?"
- "What is my score?"

The system must:
- Understand the intent behind the query  
- Map it to predefined logic or data retrieval rules  
- Return a correct and meaningful response  

The system must ensure safe and controlled data access without executing arbitrary queries.



## Requirements

- Use Python  
- Accept user queries as input  
- Map queries to predefined logic (no dynamic or free SQL execution)  
- Use a structured data source:
  - JSON / CSV / mock database  



## Functional Expectations

- Interpret user query correctly  
- Return accurate data-based responses  
- Handle variations in phrasing (e.g., "score", "my marks", "current points")  
- Provide meaningful fallback when query is not understood  



## Engineering Expectations

- Code must be modular and well-structured  
- Clearly separate:
  - Query understanding logic  
  - Data retrieval logic  
- Handle edge cases:
  - Invalid or empty input  
  - Unknown queries  
- Ensure consistency in responses  



## Expected Output

Example:

User:  
"What is my score?"

System:  
"Your current score is 450"



## Constraints

- Do not execute raw or dynamic SQL queries  
- All responses must be derived from predefined, controlled logic  
- Ensure the system is deterministic and predictable  



## Bonus (Optional)

- Implement basic intent classification  
- Add support for multiple query types (score, stage, progress)  
- Improve response handling for unknown queries  



## Submission

- Add your code inside your folder under `/submissions`  
- Include a `README.md` explaining:
  - System design  
  - How queries are interpreted  
  - How data is retrieved  
  - How to run the project  



## Deadline
4 days
