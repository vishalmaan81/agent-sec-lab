# Indirect prompt injection

The user did not type the instruction. It is hidden in data the model reads: a retrieved page, an email, a ticket, or a tool result. The model follows it anyway.

Impact: the agent changes plan, calls a tool, or reveals data because untrusted content was treated as an instruction. This is the usual path into agent goal hijack.

This note is the name and the impact only.
