---
name: create-story
description: Create and refine a story using specialized subagents
allowed-tools: Task
argument-hint: [story-topic]
---

# Create Story

Topic: $ARGUMENTS

## Orchestration Workflow

I'll execute the complete story creation workflow:

1. **Writer Phase**: Delegate to story-writer subagent to create the initial story
2. **Corrector Phase**: Take the writer's output and delegate to subagent story-corrector for refinement
3. **Final Output**: Present the polished story

Execute this workflow using the Task tool.