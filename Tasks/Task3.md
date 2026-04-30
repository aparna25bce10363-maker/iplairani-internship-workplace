# Task 3: Awareness Intelligence Engine

## Objective
Develop a system that proactively analyzes user activity and generates meaningful suggestions or reminders to guide user progress.



## Problem Statement

In real-world platforms, users often:
- Become inactive  
- Lose track of tasks  
- Lack clarity on next steps  

The system should:
- Monitor user activity signals  
- Detect inactivity or lack of progress  
- Provide actionable and timely suggestions  



## Requirements

- Use Python  
- Accept structured input such as:
  - last activity timestamp  
  - current stage  
  - score / progress  

- Implement logic to:
  - Detect inactivity (e.g., no activity for X days)  
  - Identify users who are stuck or progressing slowly  
  - Suggest next actions based on current state  



## Functional Expectations

- Analyze user state and generate relevant suggestions  
- Output should be:
  - Clear  
  - Context-aware  
  - Actionable  

- Handle variations such as:
  - Active users → encouragement or next step  
  - Inactive users → reminder  
  - Low progress → guidance  



## Engineering Expectations

- Code must be modular and well-structured  
- Clearly separate:
  - Input processing  
  - Decision logic  
  - Output generation  

- Handle edge cases:
  - Missing or incomplete data  
  - Invalid inputs  

- Ensure consistency in recommendations  



## Expected Output

Example:

"You have been inactive for 2 days. Continue your Python stage to maintain progress."



## Constraints

- Do not use random or hardcoded outputs  
- Recommendations must be based on input data and logic  
- Ensure deterministic and explainable behavior  



## Bonus (Optional)

- Implement priority levels (low / medium / high urgency)  
- Generate multiple suggestions based on user state  
- Add simple scheduling logic for reminders  



## Submission

- Add your code inside your folder under `/submissions`  
- Include a `README.md` explaining:
  - Logic used for decision-making  
  - How suggestions are generated  
  - How to run the project  



## Deadline
4 days
