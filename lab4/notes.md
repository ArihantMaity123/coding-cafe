Q1. What did --global mean here? What would happen if you left it out? Guess, then check with man git-config or ask.
Ans- --global applies the configuration system-wide across all repositories on your computer. If you leave it out, the setting only applies to the current local repository.

Q2. What appeared in ls -a but not in ls? What is inside it?
Ans- The ls -a command reveals hidden files and directories including a .git directory which stores the history and other files. Whereas when we do just ls it doesnt reveal the hidden files.



