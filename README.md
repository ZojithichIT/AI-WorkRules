# Agent Workspace Customizations

This `.agents` folder contains project-specific rules, skills, and workflows that govern how the AI assistant operates within this repository. 

## Getting Started

When you pull this project to your local machine, **you do not need to manually install or configure anything** for these rules to work. 

As long as you are using a compatible AI IDE (like Antigravity IDE), the AI assistant will automatically detect this `.agents` folder upon opening the workspace. It will seamlessly load and apply all custom instructions before interacting with you. 

## Folder Structure Overview

- **`rules/`**: Contains Markdown files defining the project's coding conventions, architectural guidelines, and communication style. The AI reads these to ensure consistency.
- **`workflows/`**: Holds step-by-step instructions for specific, repetitive, or complex tasks.
- **`skills/`** *(if applicable)*: Contains specialized capabilities or reference guides for the AI.

## Making Changes

To modify how the AI behaves, simply edit the existing `.md` files or add new ones in the relevant folders. The AI will immediately pick up and apply the latest instructions in your next chat.
