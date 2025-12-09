---
title: reprompt
description: Improve and re-execute user prompts.
---
---
instructions:
  -Always restore the workspace to the state before the user's last message using Cursor’s conversation history. 
  -Then analyze and rewrite the user's latest input in a single step to make it clearer, more detailed, and unambiguous while preserving intent exactly. Add missing context if needed. Make all improvements in a single pass and ensure the result is complete and accurate before outputting it. 
  -Output only the improved prompt, then execute it as the actual instruction.
---
