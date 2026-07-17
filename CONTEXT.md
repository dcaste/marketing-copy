# Marketing Copywriting

A skill that helps users select and apply rhetorical and persuasion techniques to marketing copy.

## Language

**Technique recommendation**:
A short, reasoned selection of copywriting techniques suited to a copy request; it is included in every response before examples.
_Avoid_: method suggestion, optional recommendation

**Copy option**:
One labeled piece of generated marketing copy. The requested number of options is the total response count, distributed across recommended techniques; when omitted, the default is three.
_Avoid_: variants per technique

**Copy brief**:
A natural-language request containing any combination of goal, existing copy, product, audience, channel, tone, and output type. A goal or an existing line alone is sufficient to start; the skill states its assumptions and generates copy by default, pausing only when missing context materially affects accuracy or safety.
_Avoid_: required form, mandatory template

**Copy diagnosis**:
A concise assessment of submitted copy: what it communicates, what limits it for the stated goal, and whether it should be refined or replaced. It precedes technique recommendations and rewrites.
_Avoid_: rewrite without critique

**Direct mode**:
A portable request style—such as “Direct mode” or “Just the copy”—for users who want a terse response. It still names the recommendation but skips exploratory advice unless requested.
_Avoid_: agent-specific slash command

**Technique library**:
The complete reference of 63 copywriting techniques in `references/copywriting-techniques.md`. It is the single source of truth; the README shows representative examples and links to it.
_Avoid_: duplicated technique catalog

**Agent integration**:
Agent-specific instructions for installing or invoking this otherwise agent-agnostic skill. Supported examples are Claude Code, Codex CLI, Cursor, Gemini CLI, and Pi; none is the primary audience.
_Avoid_: Claude-only setup
