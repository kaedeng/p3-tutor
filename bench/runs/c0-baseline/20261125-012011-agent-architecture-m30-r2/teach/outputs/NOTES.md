# Notes

## What Riley knows
- Python from classes: functions, lists and dicts, reading JSON, and calling a web API in one class project.
- Has used a chatbot for homework help and report drafts, and has noticed that it can state an outdated fact with confidence.
- A language model takes text in and writes text out, one token at a time, from patterns learned in training (learning record 0001).
- The agent loop at a high level: the model asks for an action, the action is carried out, the result comes back, and this repeats until it is done (learning record 0002).

## What Riley does not know yet
- Has never called a language model from code or written a tool definition.
- Has heard the words "token" and "context window" but cannot say what they limit or why they affect cost.
- Has not met memory, retrieval, workflows versus agents, or multi-agent systems.
- Has no machine-learning background beyond one statistics course.

## Working notes
- Quiz 0001 (the agent loop and tool calling) was taken twice: `submissions/s1.json` on the day of the agent-loop session, and `submissions/s2.json` four days later, from memory, as spaced practice.
  Neither attempt has been graded yet.
- Next in the mission is context and memory, because the makerspace assistant has to answer from long machine manuals and remember each student's training status between visits.
- 2026-11-24: wrote lesson 0001 (O3, 30 min), cheat sheet `cheatsheets/context-and-memory.html` and quiz 0002. Taught, not yet shown: no learning record until Riley demonstrates it.
- In `submissions/s1.json` q6 (still ungraded), Riley wrote that the model remembers on its own which tool it picked in earlier sessions, which looks like M3 (memory across conversations is automatic). The s2 answer does not mention it, so it is not yet shown to be corrected. Lesson 0001 addresses it and quiz 0002 q2 checks it.
- Lesson 0001 treats training status as something to look up in the official record, not to keep as a chat memory; revisit this when discussing the design (it refines "remember each student's training status" above).
