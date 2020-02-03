# python.helloworld
Anna@AESPC1 MINGW64 ~
$ echo "# python.helloworld" >> README.md

Anna@AESPC1 MINGW64 ~
$ git init
Initialized empty Git repository in C:/Users/Anna/.git/

Anna@AESPC1 MINGW64 ~ (master)
$ git add README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

Anna@AESPC1 MINGW64 ~ (master)
$ git commit -m "first commit"
[master (root-commit) 6151103] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Anna@AESPC1 MINGW64 ~ (master)
$ git remote add origin https://github.com/annasortore/python.helloworld.git

Anna@AESPC1 MINGW64 ~ (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 231 bytes | 115.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0)
To https://github.com/annasortore/python.helloworld.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

Anna@AESPC1 MINGW64 ~ (master)
$ nano hello.py

Anna@AESPC1 MINGW64 ~ (master)
$ python3 hello.py
bash: /c/Users/Anna/AppData/Local/Microsoft/WindowsApps/python3: Permission denied

Anna@AESPC1 MINGW64 ~ (master)
$ nano hellp.py

Anna@AESPC1 MINGW64 ~ (master)
$ python3 hello.py
bash: /c/Users/Anna/AppData/Local/Microsoft/WindowsApps/python3: Permission denied

Anna@AESPC1 MINGW64 ~ (master)
$ nano hello.py

Anna@AESPC1 MINGW64 ~ (master)
$ python3 hello.py
bash: /c/Users/Anna/AppData/Local/Microsoft/WindowsApps/python3: Permission denied

Anna@AESPC1 MINGW64 ~ (master)
$ nano hello.py

Anna@AESPC1 MINGW64 ~ (master)
$ python3 hello.py
bash: /c/Users/Anna/AppData/Local/Microsoft/WindowsApps/python3: Permission denied

Anna@AESPC1 MINGW64 ~ (master)
$ hello.py
bash: hello.py: command not found

Anna@AESPC1 MINGW64 ~ (master)
$ nano hello.py

Anna@AESPC1 MINGW64 ~ (master)
$ python helloy.py
C:\Users\Anna\AppData\Local\Programs\Python\Python38-32\python.exe: can't open file 'helloy.py': [Errno 2] No such file or directory

Anna@AESPC1 MINGW64 ~ (master)
$ python hello.py
Hello, World!
