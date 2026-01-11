---
name: analyze-character
description: Deep analysis of a character
allowed-tools: Task
argument-hint: [character-name]
---

# Analyze Character

Character: $ARGUMENTS

1. Delegate to character-analyzer subagent: "Analyze this character: $ARGUMENTS"
2. Delegate to psychology-expert subagent: "Provide psychological analysis of this character"
3. Combine insights and return comprehensive analysis