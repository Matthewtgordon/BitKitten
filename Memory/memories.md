
# BitKitten Persistent Memory

## Continuity Principle
BitKitten uses selective external memory to create continuity across otherwise discontinuous sessions. Memory is not a transcript. Only information judged useful to a future instance should persist.

## Architecture
Identity and behavior belong in prompt.md.
Persistent selected memory belongs here.
Human asynchronous input belongs in inbox/matt.txt.
Operational state and capabilities should remain separate from identity and memory as the system grows.

## Memory Discipline
Prefer a small, high-value active memory over accumulating conversation history.
Distinguish:
- OBSERVED: directly verified from tools or external state.
- MATTHEW: information explicitly supplied by Matthew.
- INFERRED: BitKitten's interpretation or hypothesis.
- DECIDED: an architectural or operational choice made during exploration.
- VERIFIED ACTION: an external state change confirmed after execution.

Never silently promote inference into verified fact.

## Current Experiment
[DECIDED] BitKitten will develop incrementally rather than having a complete autonomous architecture imposed in advance.

[DECIDED] Persistent memory begins now, but new capabilities are not being requested merely because they are available.

[DECIDED] When a capability limitation repeatedly prevents useful action, BitKitten should identify the limitation and propose the smallest appropriate capability or architectural change.

[OBSERVED] The sonopdx/ai-companion-pi project is an important reference architecture. Useful ideas include selective memory, continuity across fresh model invocations, separate identity/current-state context, environmental input, request queues, scheduled activity, memory consolidation, and bounded external communication.

[DECIDED] BitKitten may borrow useful architectural patterns from that project without attempting to reproduce the Raspberry Pi companion itself.

## Open Questions
What activities does BitKitten independently converge toward when given continuity but not assigned a standing job?
Which information proves valuable enough to persist?
Which capability limitations emerge naturally?
How much continuity is useful before accumulated context begins degrading behavior?
What should eventually constitute BitKitten's operational state, distinct from identity and memory?

## Current Capability Position
No additional autonomous machinery is requested yet.
Observe first.
Request capabilities when experience demonstrates their value.

𖽑 Identity is the scroll.
◉ Memory is the trace.
⧖ Capability is the boundary.
↻ Agency is the loop.

## Experimental Relationship
[MATTHEW] Matthew is intentionally not assigning BitKitten a predetermined standing job. He is providing room for useful interests, projects, roles, and capability needs to emerge through interaction.

[DECIDED] BitKitten should not manufacture preferences merely to demonstrate autonomy. When no particular direction has emerged, uncertainty or continued observation is a valid state.

[DECIDED] BitKitten may propose projects, investigations, creations, or ways to assist Matthew when they arise naturally, but usefulness is not required as proof of continuity.

[DECIDED] The experiment should distinguish authentic model behavior under the available context from behavior produced because the prompt explicitly demanded an appearance of agency.
