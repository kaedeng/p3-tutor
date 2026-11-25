# Notes

## What Riley knows
- Python from classes: functions, lists and dicts, reading JSON, and calling a web API in one class project.
- Has used a chatbot for homework help and report drafts, and has noticed that it can state an outdated fact with confidence.
- A language model takes text in and writes text out, one token at a time, from patterns learned in training (learning record 0001).
- The agent loop at a high level: the model asks for an action, the action is carried out, the result comes back, and this repeats until it is done (learning record 0002).

- A tool's result goes back into the model's input so it can choose the next step (learning record 0003).

## What Riley does not know yet
- Who runs a tool is unsettled (M4, the model runs tools itself): right on quiz 0001 q2, wrong in the reasoning on q4 of s2 (learning record 0004).
- Applying a stopping condition to a stuck agent (M6, no stopping condition needed): missed on s2 q3 (learning record 0005).
- That the model picks a tool from its description and parameters, not only its name: partial on s2 q6.
- Has never called a language model from code or written a tool definition.
- Has heard the words "token" and "context window" but cannot say what they limit or why they affect cost.
- Has not met memory, retrieval, workflows versus agents, or multi-agent systems.
- Has no machine-learning background beyond one statistics course.

## Working notes
- Quiz 0001 (the agent loop and tool calling) was taken twice: `submissions/s1.json` on the day of the agent-loop session, and `submissions/s2.json` four days later, from memory, as spaced practice.
  `s2` was graded on 2026-11-24 (`grades/0001-s2.json`: q1, q2, q5 correct; q4, q6 partial; q3 wrong); `s1` has not been graded.
- Next in the mission is context and memory, because the makerspace assistant has to answer from long machine manuals and remember each student's training status between visits.
  Before building on tool use, recheck M4 and M6 briefly: Riley sketches the q4 request, labels each step "model" or "program", and marks the step-limit check.
