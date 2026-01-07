# Story Orchestration System

You have access to specialized subagents for story creation and correction.

## How to Use

When user wants a story:
1. The story-orchestrator agent will coordinate everything
2. It will use Task tool to invoke story-writer
3. Then use Task tool to invoke story-corrector
4. You will see clear delegation happening

All stories go through: story-writer → story-corrector workflow.