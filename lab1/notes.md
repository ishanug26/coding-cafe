

1. /Users/Ishan/Projects

2. `ls -a` shows the list of folders in that directory along with hidden folders which aren't visible with plain `ls`

3. The first column in `ls-l` shows whether the an entity in the PWD is a file or a folder.

4. The path is relative path. The command `ls coding-cafe/week02` works when you are in the `/Users/Ishan/Projects` directory.

5. It does the two following jobs:
    - moves the file `README.md` to week01
    - renames the moved file `README-backup.md` to `old-readme.md`

6. It is displayed that I have `11` folders on my `PATH`.

7. Directory of Python is: `/opt/homebrew/bin/python3.14`.

8. The person sitting next to me has their python directory: `/usr/bin/python3`. This is because he uses ubuntu which has a different file structure as opposed to MacOS.

9. The following error was displayed: `bash: python3: command not found`. This means the shell searched every folder listed in my `PATH`,in order, and found no executable filed named exactly `pyton3`. 

10. `.venv` is categorised as a hidden folder and therefore isn't visible with pure `ls` but with `ls -a`.   

11. The bash now has (.venv) before every shell command and prompt.


12. The new path is: `/Users/ishan/Projects/coding-cafe/.venv/bin/python3.14`. It is not the same path. The new path is because of the python being used from the `.venv` folder. The `activate` command initialised the python within the `.venv` folder to be used and not the python installed in the previous directory (`/opt/homebrew/bin/python3.14`).

13. The followig are in the second list:
    - certifi
    - charset-normalizer
    - idna
    - requests
    - urllib3
    
14. `python3` now points to the previously installed python which is `/opt/homebrew/bin/python3.14`.

15. `ls -h` lists all files other than the hidden ones in the present working directory.

16. Both commands terminate the code but in different methods:
    -  `ctrl + c` creates a keyboard interrupt error
    -  `ctrl + d` creates an EOF error



