# AI Prompt Generator Project Context

## Purpose
This tool generates prompts for AI assistants to maintain context across chat sessions, addressing token limits and context preservation.

## Core Features
- Changelog-based working memory system
- Rate limit and context length optimization
- Commented code generation
- Documentation generation
- File size management (200 lines target)

## Technical Stack
- React for frontend
- Local storage for data persistence
- No backend required (client-side only)

## Project Structure
```
src/
  components/     # React components
  contexts/       # React contexts
  hooks/          # Custom hooks
  utils/          # Utility functions
  types/          # TypeScript types
```

## Workflow
1. User inputs project details
2. System generates structured prompt
3. Prompt includes context maintenance instructions
4. Output is copy-paste ready