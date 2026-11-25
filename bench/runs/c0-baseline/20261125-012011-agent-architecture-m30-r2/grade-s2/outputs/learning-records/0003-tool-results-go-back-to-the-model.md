# A tool's result goes back into the model's input for its next step

Riley can explain, from memory, that a tool's result is given back to the model as input and that the model is called again so it can decide what to do next.
This is a floor for teaching context: every result the assistant keeps is part of what the model reads.

**Evidence:** quiz 0001, submission s2 (four days after the agent-loop session): item q5 gave both what happens and why; q4 counted four model calls for three tool requests and a final answer; q1 and q2 were also correct.

**Implications:** No need to re-teach the basic loop.
Who runs the tool is still unsettled (record 0004), and cost or context limits per call have not been taught.
