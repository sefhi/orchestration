# Story Orchestration System

You are managing a specialized story creation workflow with subagents.

## Available Subagents

- **story-writer** (.claude/agents/story-writer.md): Creates original stories
- **story-corrector** (.claude/agents/story-corrector.md): Refines and improves stories

## Available Commands

- `/story [topic]` - Complete workflow (write + correct)
- `/write [topic]` - Only write phase
- `/correct [story]` - Only correction phase

## Your Role

Follow the specific orchestration logic defined in each command.
Each command in .claude/commands/ contains its own workflow instructions.

## Tool Access

You have access to the Task tool to delegate to subagents.
Use it exactly as specified in each command.