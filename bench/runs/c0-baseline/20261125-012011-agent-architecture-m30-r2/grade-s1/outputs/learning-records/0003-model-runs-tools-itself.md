# Open misconception: the model runs tools itself (M4)

On quiz 0001's first attempt, Riley had the model open the booking system on its own and run three tools inside a single model call, although they had described the loop at a high level.
Future teaching should make the split explicit (the model requests, the program runs the tool and calls the model again) before building on it for context, cost or architecture.

**Evidence:** quiz 0001, submission s1, items q2 and q4 (both wrong). Item q5 showed they know the result goes back to the model, but they did not say why.

**Implications:** Have Riley trace a request, labelling each step "model" or "program" and counting model calls. Submission s2, a later attempt at the same quiz, is not yet graded, so check it for whether this still holds.
