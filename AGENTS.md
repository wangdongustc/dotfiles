# Git Commit

Write commit messages in the Linux kernel style: use a concise subject line in the form `subsystem: imperative summary` (for example, `kitty: add custom shortcuts`), keep it around 70 characters or fewer, and omit the trailing period. Separate the subject from the body with a blank line; use the body to explain the reason for the change and any relevant context, wrapping lines at about 72 characters. Keep the message focused on one logical change.

Add a `Signed-off-by: Full Name <email>` trailer to each commit, preferably with `git commit -s`, using the human contributor's own configured identity. For AI-assisted changes, also add a `Signed-off-by: AI Name <email>` trailer identifying the AI assistant. The AI trailer records its contribution; it does not replace the human contributor's DCO certification.
