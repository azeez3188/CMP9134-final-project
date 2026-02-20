# AI Verification Log

This log documents all AI tool interactions used during the development 
of the Robot Management System, in compliance with Assessment 1 regulations.

---

## Entry 1

**Date:** 20/02/2026  
**AI Tool Used:** Claude (Anthropic)  
**Task:** Task 4 – Validating Requirements with an AI Stakeholder Persona

### Prompt Used:
"Act as the Chief Safety Officer for a warehouse deploying a new Virtual 
Robot Management System. I am the lead software engineer. Please review 
my User Story and Acceptance Criteria for navigating the robot and tell me:
1. Are there any safety, security, or usability edge cases I missed?
2. Is the language clear enough for a non-technical stakeholder to approve?"

### AI Suggestion:
The AI identified that there was no confirmation prompt before the robot 
moves, which could cause accidental movement. It suggested adding: 
"The system must display a confirmation dialog before executing any move command."

### How I Validated It:
This is a valid safety concern — in a real warehouse, accidental robot 
movement could injure staff. The suggestion aligns with standard safety 
engineering practice.

### How I Applied It:
Added the confirmation prompt requirement to the Acceptance Criteria on 
the Trello card for the "Navigate Robot" User Story.

---