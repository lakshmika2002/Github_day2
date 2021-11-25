
cisco@itlab3-27 MINGW64 ~/Desktop
$ mkdir day2

cisco@itlab3-27 MINGW64 ~/Desktop
$ cd day2

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ touch text1.txt

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ notepad file1.txt

pwd

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ notepad file1.txt

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ pwd
/c/Users/cisco/Desktop/day2

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ touch file2.txt

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ notepad file2

cisco@itlab3-27 MINGW64 ~/Desktop/day2
$ git init
Initialized empty Git repository in C:/Users/cisco/Desktop/day2/.git/

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        file1.txt
        file2.txt
        text1.txt

nothing added to commit but untracked files present (use "git add" to track)

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git addd .
git: 'addd' is not a git command. See 'git --help'.

The most similar command is
        add

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git add .

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   file1.txt
        new file:   file2.txt
        new file:   text1.txt


cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.name

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.name lakshmika

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.name
lakshmika

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.email

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.email lakshmika2002@gmail.com

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git config user.email
lakshmika2002@gmail.com

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git commit -m "day2"
[master (root-commit) 1fa9761] day2
 3 files changed, 12 insertions(+)
 create mode 100644 file1.txt
 create mode 100644 file2.txt
 create mode 100644 text1.txt

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git remote

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git remote add remote2 https://github.com/lakshmika2002/Github_day2.git

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$ git remote
remote2

cisco@itlab3-27 MINGW64 ~/Desktop/day2 (master)
$

