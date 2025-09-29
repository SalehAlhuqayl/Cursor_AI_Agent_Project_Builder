# Cursor AI Agent Project Builder

A smart system that helps you build complete projects using Cursor's AI agent with advanced memory management.

## What This Does

This project uses two main files to help the AI agent understand and build your projects:
- `project_planner.md` - Creates detailed project plans  
- `Memory_Bank.mdc` - Keeps the AI agent's memory between conversations

## Requirements

**Important:** Install the "Markdown Preview Mermaid Support" extension in Cursor before starting.

## How to Use

### Step 1: Create Your Project Plan

1. Start a new chat with the AI agent
2. Type: `@based on project_planner.md` 
3. Add your project description. Examples:
   - "Create an Arabic blog website"
   - "Build a GPA calculator website" 
   - "Make a task management app"

**Result:** The agent creates a `project_description.mdc` file with your complete project plan.

### Step 2: Check Your Project Plan

Read the `project_description.mdc` file and make sure it matches what you want to build.

### Step 3: Initialize Memory Bank

1. Start a **new chat** with the agent
2. Type: `initialize @Memory_Bank.mdc based on the @project_description.mdc`

**Result:** The agent creates these memory files:
- `active_context.mdc`
- `product_context.mdc` 
- `progress.mdc`
- `project_brief.mdc`
- `system_patterns.mdc`
- `tech_context.mdc`

### Step 4: Set Up Always Apply

Convert each `.mdc` file to "Always Apply" in Cursor. This means the agent will read these files in every conversation.

### Step 5: Start Building

Ask the agent to start the project. The agent will now:
- Remember everything about your project
- Work step by step
- Update progress automatically
- Keep track of what's done and what's next

## Why This Works

The Memory Bank system solves a big problem: AI agents forget everything between conversations. This system:

- Keeps detailed project memory in organized files
- Tracks progress and current tasks  
- Remembers technical decisions and patterns
- Documents problems and solutions

## Tips for Success

- Always use "Always Apply" for all `.mdc` files
- Let the agent finish each step before asking for changes
- The agent will ask for approval before making big changes
- Check the progress file to see what's completed

## File Types Explained

- `project_brief.mdc` - Core project goals and requirements
- `active_context.mdc` - What the agent is working on right now  
- `progress.mdc` - List of completed and pending tasks
- `tech_context.mdc` - Technologies and tools being used
- `system_patterns.mdc` - How the code is organized
- `product_context.mdc` - User needs and project purpose


## Acknowledgments
- **Abdullah Alrashoudi** — [@Abdullah4AI](https://x.com/Abdullah4AI). Creator of the Memory Bank file.  
- **Mazen Alotaibi** — [@ma7dev](https://x.com/ma7dev). Recognized as a **Cursor** ambassador and for sharing valuable resources about the platform.

---

**Ready to build? Follow the steps above and let the AI agent create your complete project!**
