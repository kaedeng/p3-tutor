# Misconception to work on: the model runs the tools itself (M4)

In quiz 0001, submission s1, Riley treated the model as the thing that carries out tools, so the split between model and program, and the separate model call at each step, is not yet secure.
It should be addressed before building on the loop, because tool definitions, cost per request and the architecture all depend on it.

**Evidence:** q2, chose that the model reads the calendar by opening the booking system; q4, answered 1 model call because the model "runs the 3 tools itself". In q5 Riley did say the result is sent back to the model, but gave no reason.

**Implications:** Have Riley trace a request with model actions and program actions kept apart, and count the model calls.
This reflects s1 only, taken on the day of the agent-loop session; s2 had not been graded when this was written.
