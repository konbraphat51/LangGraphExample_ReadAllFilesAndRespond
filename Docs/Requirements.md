# Requirements
## Function
Create a simple LangGraph CLI that responds to the user prompt, but ensures to read all files in the specified directory.

### Workflow
1. receive user prompt and directory specification via CLI.
2. Read each document file (.txt or .md) in the directory, while editing a note as long-term memory.
3. After reading all, infer what to respond based on the note.
  - Here, provide a tool for grep search, or read a document specified by filename. 
5. Print out a response.

## Implement
- Implement in Python 3.12 + latest Langgraph + uv
- Create a SOLID structure.
- Separate Node, Edge, State, Graph file for the application layer.
- Create a log file.
- Set model and OpenAI API key with `dotenv`
- Write document with class diagram and sequence diagram in mermaid
