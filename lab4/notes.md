Q1: --global saves my name and email for every repository on this computer. Without it, the setting would apply only to the current repository.
Q2: ls -Force shows a hidden folder called .git. It holds the whole history: objects, refs, HEAD, config, index and hooks.
Q3: Git offered to track about 2 items (week01 and README.md). Nothing looked unfamiliar since I have no .venv.
Q4: Nothing disappeared because I have no .venv, __pycache__ or .DS_Store. Only .gitignore appeared as a new untracked file.
Q5: .gitignore should be committed so the ignore rules are saved in the history and shared with everyone who uses the repo.
Q6: README.md moved from "Changes not staged for commit" to "Changes to be committed". That is working directory to staging area.
Q7: Git printed [main 6922f20] Write README and add .gitignore, then 2 files changed, 12 insertions(+), 5 deletions(-).
Q8: 6922f20 is the short commit hash. It is a unique ID for that commit so I can refer to it later.
