---
name: review-checklist
description: Short checklist for reviewing a change before it is merged. Use when asked to review a diff, a branch or a pull request.
---

# Review checklist

Check, in this order, and report only what you found:

1. Does the change do what its description says, and nothing else?
2. Are errors handled, and do failures stay visible instead of being swallowed?
3. Are there tests for the new behavior, including the failure path?
4. Could it break existing users (config, API, file formats, defaults)?
5. Are secrets, tokens or personal paths left in code, logs or comments?
