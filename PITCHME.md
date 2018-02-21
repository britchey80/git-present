@title[Introduction]

# Git
## <span class="gold">Command Line Basics</span>

#### A primer on navigating the Git command line

---
@title[Getting Started]
### Getting Started
<br>
#### Debian
```shell
$ apt-get install git
```
<br>
#### CentOS
```shell
$ yum install git
```
<br>
#### MacOS
```shell
$ brew install git
```


---
@title[sample code]
### Status and Add

```shell
$ echo "This is my first file" > test.txt
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

    test.txt

nothing added to commit but untracked files present (use "git add" to track)
$ git add test.txt
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

    new file:   test.txt

$
```

@[1](Add a new file to the repository)
@[2-11](Check status of files)
@[12](Use git add to prepare for commit)
@[13-20](Check status to show changes to be committed)