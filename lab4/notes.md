Answers for given questions

Ans 1. `--global` means that the changes to the configuration using `git config` should apply for all the repositories on your operatng system. If `--global` isn't written, the configuration applies only to the current repository the user is in, that is, it is considered to be `--local`.

Ans 2. When `ls -a` is used as opposed to `ls`, we are able to see the hidden folders, primarily the `.git` folder which is not visible when `ls` is used.

Ans 3. Git is currently not tracking any files or folders. 

Ans 4. Git is currently not tracking any files. It says one file, which is `.gitignore` is currently untracked. When `git status` is written in quesiton 4, it shows an extra untracked file which wasnt showed earlier in question 3.

Ans 5. `.gitignore` which shows up as untracked should also be committed, and not be ignored. This is because files such as those in the `.venv` folder are hard coded for the user's personal operating system and should not be carried onto the system of another user.

Ans 6. `README.md` moved from `untracked` to `modified` heading in the `git status` output. When the command `git add README.md` is carried out, it moves from the `working directory` to the `staging area` when the command is carried out,

Ans 7. It printed the following when the command was carried out.

    [main (root-commit) 27de216] Lab work so far
    2 files changed, 4 insertions(+)
    create mode 100644 .gitignore
    create mode 100644 README.md`

It changed 2 files in total.

Ans 8. The first seven characters (27de216) are called a short commit hash (or short SHA-1 checksum). They are a unique key that helps to identify the specific commit in the repository history.

Ans 9. The 4 steps of git cycle are:
-> Edit
-> Check
-> Stage
-> Commit

Ans 10. `README.md` is given a standard name and is placed directly into the root direcotry because platforms like GitHub automatically detect and render it on the project's front page. It provides visitors and collaborators with an immediate overview of the project and also helps the collaborators communicate with the 

Ans 11. `gh auth login` authenticates the terminal using web authentication and allows you to access your github account through your machine. This eliminates the need for you to type your password when you need to execute `git push`. 

Ans 12. Refreshing the repository page shows the contents of `README.md` formatted on the home page of the repository. GitHub automatically renders README.md because it is designated as the repository's default landing document to tell the visitors of the repository about the current repository.

Ans 13. Running `git log --oneline` shows that pushing did not affect the local commit history or hash at all. It updated the tracking pointers and now the origin points to the same commit as your local master head.

Ans 14. A private repository exists on GitHub's servers but it limits the access of the repository to the its original owner and the collaborators invited by the owner, therefore keeping the code hidden from the general public. If a respository does not exist on GitHub at all, no remote copy or history exists. 


