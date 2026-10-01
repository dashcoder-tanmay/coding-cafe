Q1: --global saves my name and email for every repository on this computer. Without it, the setting would apply only to the current repository.
Q2: ls -Force shows a hidden folder called .git. It holds the whole history: objects, refs, HEAD, config, index and hooks.
Q3: Git offered to track about 2 items (week01 and README.md). Nothing looked unfamiliar since I have no .venv.
Q4: Nothing disappeared because I have no .venv, __pycache__ or .DS_Store. Only .gitignore appeared as a new untracked file.
Q5: .gitignore should be committed so the ignore rules are saved in the history and shared with everyone who uses the repo.
Q6: README.md moved from "Changes not staged for commit" to "Changes to be committed". That is working directory to staging area.
Q7: Git printed [main 6922f20] Write README and add .gitignore, then 2 files changed, 12 insertions(+), 5 deletions(-).
Q8: 6922f20 is the short commit hash. It is a unique ID for that commit so I can refer to it later.
Q9: The loop is: edit a file, check with git status, stage with git add, and save with git commit.
Q10: README.md has a special name and place because GitHub shows it on the repository front page, so it works as the first thing a visitor reads.
Q11: gh auth login signs me in through the browser and saves a login token on my computer, so Git uses it instead of asking for a password on each push.
Q12: The front page shows the README.md, because GitHub automatically displays the README in the root of a repo.
Q13: No. Pushing only copies my commits to GitHub. My local history stays the same, except that origin/main moves up to match main.
Q14: A private repository exists on GitHub but only I and the people I invite can see it. If it did not exist at all, there would be nothing on GitHub, no backup, and nothing for the TAs to open.
