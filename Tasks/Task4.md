# Task 4: Action Intelligence Engine

## Objective
Develop a system that can interpret user instructions and execute actions such as setting reminders or scheduling tasks.



## Problem Statement

Users should be able to interact naturally with the system to:
- Set reminders  
- Trigger simple actions  

The system must:
- Understand the intent of the user  
- Extract relevant details (time, task, etc.)  
- Store and simulate execution of the action  



## Requirements

- Use Python  
- Accept natural language input such as:
  - "Remind me to study at 6 PM"
  - "Set a reminder for tomorrow at 9 AM to revise"

- The system should:
  - Parse user intent  
  - Extract key parameters (task, time)  
  - Store reminders in a structured format (JSON / in-memory / file)  



## Functional Expectations

- Interpret user input correctly  
- Confirm the action to the user  
- Maintain a list of scheduled reminders  
- Simulate execution (e.g., print reminder at scheduled time or trigger check)



## Engineering Expectations

- Code must be modular and well-structured  
- Clearly separate:
  - Input parsing  
  - Action handling  
  - Storage logic  

- Handle edge cases:
  - Invalid time formats  
  - Missing task description  
  - Ambiguous input  

- Ensure consistency and reliability of outputs  



## Expected Output

Example:

User:  
"Remind me to study at 6 PM"

System:  
"Reminder set for 6 PM: Study"



## Constraints

- Do not rely entirely on external automation platforms  
- Core logic for parsing and storing reminders must be implemented  
- Ensure deterministic and explainable behavior  



## Bonus (Optional)

- Implement scheduling logic (trigger reminders based on time)  
- Support multiple reminders  
- Add update/delete reminder functionality  



## Submission

- Add your code inside your folder under `/submissions`  
- Include a `README.md` explaining:
  - System design  
  - How reminders are parsed and stored  
  - How to run the project  



## Deadline
4–5 days
