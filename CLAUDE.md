# GitHub push workflow

When I say "send this to GitHub":
1. Take the text of my (Claude's) last response in this session.
2. Save it as a plain text .txt file in this repo.
3. Name it: YYYY-MM-DD-topic-slug.txt (topic slug from the content, lowercase, hyphenated).
4. If a folder structure by theme doesn't exist yet, ask me once whether to create one (e.g. /macro, /podcast, /misc) or default to a flat root.
5. git add, commit with message "Add: <topic>", and push to main.
6. Confirm the file path and commit hash back to me.

Repo: git@github.com:wewelivia/CDum.git
