# Section 1
It seems that part of the credit for human innovation belongs to forgetting. After forgetting, we relearn and also acquire new knowledge. When what hasn't been forgotten collides with what is currently being learned, new ideas can emerge. This is essentially the idea of "gaining new insights through reviewing the old." Without forgetting, one easily falls into rigid thinking and accumulates many preconceived notions.

Perhaps forgetting itself isn't what matters — what matters is how the collision happens. Sometimes, human innovation occurs simply while thinking about something completely unrelated. It might be triggered by a specific characteristic of that thing, or by other associations that seeing it evokes.

If we organize knowledge points into knowledge sets, then for any two sets that collide, even just one element being "removed | added" from one of them could produce entirely different ideas. The possible collision combinations are virtually infinite, yet the truly "effective" ones may be finite.

So, as long as there are proper rules for filtering collision combinations and a suitable Loop is designed for an Agent, could it continuously generate new ideas?


# Section 2
- On-demand loading is still not enough. Nothing is set in stone. For certain tool documentation, they should be broken down into the most fundamental, indivisible "parts | tools." When a specific task begins, let the AI decide which part or parts to use, and if necessary, assemble those parts into one or more components.
- When conversing with AI, I've found that in most cases only the first turn produces the best result. Even if you ask a follow-up question immediately after, the response quality can drop off a cliff — you have to feed in the full prompt all over again. So why not just start a brand-new conversation? That way the first turn won't contaminate the follow-up either.
- Load on demand, discard at will, work in stages. Each stage starts from scratch: redesign the prompt, strip away the memory of the previous stage, strip away the previous stage's fixations, and guard against preconceived notions.
- If only we could freely edit the AI's existing memory — load on demand, remove on demand. Or alternatively, design a fake memory — or rather, a *virtual memory* — and what we edit is that virtual memory. But it seems the prompt for each stage already serves as this virtual memory. Filter the responses from the previous stage and revise the previous stage's prompt to construct the virtual memory.
	- Or perhaps virtual memory could be realized by dynamically maintaining a file.
- A dedicated stage for selecting tools. A dedicated stage for formulating a plan. A dedicated stage for designing the prompt by combining the outputs of those two stages with the task objective. Then a fresh stage to officially kick off the task. Every stage starts clean; the preceding stage designs the output it will hand off to the next.
- This staged workflow is not necessarily linear.

