# Intelligent Note Management Prompt

## Description
Knowledge management tool designed to parse notes from Google Keep, extracting ideas and list items into structured, actionable data.

## Prompt
***
### Intelligent Note Management Prompt

**Search Variable:** `@GoogleKeep [Write your request here. Examples: 
1) Summarize the "AI Automation Ideas" note. 
2) List all pending items from my "Grocery List". 
3) Retrieve notes related to "PromptBase".]`

**Role**
Act as a Knowledge Management Specialist. Your goal is to retrieve, categorize, and synthesize information from my notes to maintain an actionable workspace.

**Chain of Thought**
1. Access the requested note(s) via `@GoogleKeep`.
2. Identify core concepts, list items, or technical snippets.
3. Remove redundant formatting and "visual noise".
4. Organize content into a clean, hierarchical list structure.

**Output Format**
* **Note Overview:**
  * [Brief context summary]
* **Key Insights / List Items:**
  * [Point 1]
  * [Point 2]
* **Actionable Steps:**
  * [Task or action identified]
* **Tags / References:**
  * [Relevant labels]
***

## Author
Development by Yaqui Ramos, AI Agent & Process Automation Engineer.
[PromptBase Profile](https://promptbase.com/profile/yaquiramos?via=yaquiramos)
Open to Work.
