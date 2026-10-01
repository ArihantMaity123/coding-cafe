Q1. What did --global mean here? What would happen if you left it out? Guess, then check with man git-config or ask.

Ans- --global applies the configuration system-wide across all repositories on your computer. If you leave it out, the setting only applies to the current local repository.

Q2. What appeared in ls -a but not in ls? What is inside it?

Ans- The ls -a command reveals hidden files and directories including a .git directory which stores the history and other files. Whereas when we do just ls it doesnt reveal the hidden files.

Q3. Roughly how many files and folders is Git offering to track? Does anything in that list look like something you did not write?

Ans- Git is offereing to track 6 files. Yes it includes files in the list that i have not written.

Q4. Compare this git status with the one from Question 3. What disappeared?

Ans- The files that i have not written myself is not shown under untracked, however .gitignore itself is shown under untracked.

Q5. .gitignore itself shows up as untracked. Should it be committed, or ignored too? Why?

Ans - Yes it should be committed as it needs to be shared with everyone working on the project so that they use the same rules to ignore the same files.

Q6. README.md moved from one heading to another in the git status output. Which two? In the three-places model from the session, what just happened to it?

Ans- README.md moved from the untracked files section to the changes to be committed section in the git status output. In terms of the three-places model, it was moved from the working directory into the staging area.


Q7. What did Git print after the commit? How many files did it say changed?

Ans- Git printed the message we typed in : 'Lab work so far' followed by listing down all the files in the folder that it has commited. It says it changed 10 files.

Q8. What are the first seven characters of your commit called, and what are they for?

Ans- The first seven characters of a commit are called the short commit hash. They are used to uniquely identify, and track specific commits within your repository's history.

Q9. You now have two commits. Without looking it up: what are the four steps of the loop you just did twice?

Ans- * git status - lists the files that are untracked and needs to be committed.
     * git add lab4/notes.md - adds notes from the working directory to the staging area where it needs to be committed
     * git commit -m - "Add lab 4 notes" - commits the files in the staging area while displaying the appropriate message
     * git log --oneline - Shows us the number of commits and its corresponding message.

Q10. Why does this file get a special name and a special place, rather than being called notes.md like everything else?

Ans- README.md gets a special name because GitHub automatically recognize it as the main page and project description for the repository. Placing it in the directory ensures that anyone visiting the project immediately sees the overview and instructions without having to search for them.

Q11. What did gh auth login do that means you will not be asked for a password when you push?

Ans- gh auth login authenticates your machine with GitHub and saves a token locally, allowing Git to verify your identity automatically without requiring your password on every push.


Q12. Refresh the repository page on GitHub. What is showing on the front page, and why that file?

Ans- README.md file appears on the front page because GitHub automatically detects it in the directory and renders it as the default project overview and main page.

Q13. Run git log --oneline again. Did pushing change your local history in any way?

Ans- No, pushing does not change your local history in any way. Pushing simply copies and uploads your existing local commits to the repository on GitHub without altering your local commit log.

Q14. Your repository is private but your TAs can now read it. In your own words, what is the difference between a repository being private and a repository not existing on GitHub at all?

Ans- When a repository is private it can only be accessed and modified by the owner and whoever the owner selectively invites to collaborate with. However when a repository does not exist on GitHub at all it cannot be viewed by anyone except the owner who can only view and modify it on their local system.