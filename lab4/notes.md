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
