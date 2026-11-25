# Still open: who runs the tools, and what stops a stuck loop

Riley counted four model calls correctly but explained that the model runs each tool itself (M4), despite correctly choosing that the model outputs a request in another item.
Riley also chose to let a repeating agent keep running instead of adding a step limit (M6), so both ideas should be checked again before later lessons rely on them.

**Evidence:** quiz 0001, submission s2, items q4 (M4) and q3 (M6); q2 was correct.

**Implications:** Start the next session with a short retrieval exercise: label each step of a request "model" or "program" and state the stopping rule.
Also check that Riley knows the model chooses a tool from its description and parameters, since s2 q6 named only the tool's name.
