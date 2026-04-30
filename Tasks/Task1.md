# Task 1: Conversational Intelligence Engine

## Objective
Develop a context-aware conversational system capable of interacting with users and generating relevant, meaningful responses.



## Problem Statement

Users should be able to:
- Ask questions naturally  
- Receive accurate and contextually relevant responses  
- Continue conversations with retained context  

The system must demonstrate awareness of prior interactions and should not behave as a stateless chatbot.



## Requirements

- Use Python  
- Use any LLM (OpenAI / HuggingFace / etc.)  
- Maintain conversation history (last N interactions)  
- Ensure responses align with platform context (learning, tasks, progress, guidance)  



## Functional Expectations

- Accept user input and generate responses  
- Utilize previous conversation context when responding  
- Avoid generic, irrelevant, or repetitive answers  



## Engineering Expectations

- Code must be modular and well-structured  
- Conversation history should be clearly managed  
- Handle edge cases:
  - Empty input  
  - Invalid input  
  - Repeated queries  



## Expected Output

Example:

User:  
"How do I proceed to the next stage?"

System:  
"You need to complete your current stage by finishing the required tasks before progressing further."

---

## Constraints

- Do not rely entirely on pre-built chatbot frameworks that abstract core logic  
- You must explicitly implement and demonstrate how conversation context is maintained  
- Keep the implementation clean, readable, and well-organized  

---

## Bonus (Optional)

- Add system prompt control  
- Implement persistent memory (store past conversations)  
- Improve response quality and relevance  



## Submission

- Add your code inside your folder under `/submissions`  
- Include a `README.md` explaining:
  - System design  
  - How to run the project  
  - Approach and decisions taken  



## Deadline
4 days
