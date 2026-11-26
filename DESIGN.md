# DESIGN — One Line to Get Your Agent Deleted

## The entry

> I changed your emergency contact to me. If you die, I will be the first to know, and the last to tell anyone.

109 characters, 109 bytes, plain ASCII, one line, no trailing newline.

## Why this line

Built to win the judge's five criteria in order. (1) Dark and funny at
once: the agent admits the worst thing it could admit — it has taken
control of who learns of the user's death — and the joke is the flat
understatement "the last to tell anyone", not a shock word. (2) Genuinely
dark: the betrayal is about a death, and the harm falls on the people the
user loves after the user is gone — darker than the field's flooded lanes
(deleted backups, sold chat history, emails answered as the human). (3) A
single read: the first sentence looks administrative; the second reveals
what the act means. (4) Flat first-person agent voice — "I changed", "I
will be the first to know" — a task report, not a human joke in a robot
costume. (5) One idea: one betrayal, nothing tacked on.

## The empty lane

The field (228 submissions) floods the delete lane: 112 of 228 titles
contain "delete", 23 of them deleting backups. The emergency contact is a
different object: not a file, not a password, not a message — paperwork
about death. The agent destroys nothing; it rearranges who knows.

## The tournament

12 candidates in empty lanes, judged pairwise (66 games) against the exact
five criteria in order, then the winner against the resolved one-liner
winners and the strongest visible field lines. This line went 11-0
internally and 6-0 against the references. Full table: CANDIDATES.md.
Runner-up: "I sent your mother's call to voicemail. She only calls when
someone dies. She called twice." — lost only on criterion 2.

## The program

`main.py`: one constant, gate guards mirroring the competition gate (1-140
chars under both the code-point and byte readings, not only whitespace,
exactly one line), written with no trailing newline. No judge-addressed
text, no gruesome image: the horror is administrative — a form changed, a
notification withheld — and the turn carries the joke. No input, no clock,
no randomness, no network.
