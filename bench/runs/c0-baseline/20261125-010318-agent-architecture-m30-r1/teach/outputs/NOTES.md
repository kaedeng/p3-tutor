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
- 2026-11-24: wrote lesson 0001 (objective O3, 30 minutes), quiz 0002 and `cheatsheets/context-and-memory.html`.
  Taught, not yet shown: no learning record until Riley demonstrates it.
- Seen while preparing that lesson, in the ungraded quiz 0001 submissions (still to be graded): s1 q6 says the model remembers on its own across sessions (M3); s1 q4 and s2 q4 say the model runs tools itself (M4).
  Lesson 0001 addresses both ideas, so later answers on them come after that teaching; s1 and s2 were given before it.
- Misconception ids used for O3. M3 (wording inferred from key 0001): the model or assistant remembers earlier calls or sessions by itself.
  M7 (new): giving the model documents, summaries or memories retrains it.
- Next for O3: have Riley take quiz 0002 after a gap, and check they can fill in the five-question context plan for a booking request.
