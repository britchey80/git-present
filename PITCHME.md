@title[Introduction]

# Git
## <span class="gold">Command Line Basics</span>

#### A primer on navigating the Git command line

```shell
$ git add PITCHME.md
$ git commit -m "New slideshow content."
$ git push

Done!
```


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

```shell
Linodes-MacBook-Pro-2:git-present kmchale$ echo "This is my first file" > test.txt
Linodes-MacBook-Pro-2:git-present kmchale$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)

    test.txt

nothing added to commit but untracked files present (use "git add" to track)
Linodes-MacBook-Pro-2:git-present kmchale$ git add test.txt
Linodes-MacBook-Pro-2:git-present kmchale$ git status
On branch master
Your branch is up-to-date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

    new file:   test.txt

Linodes-MacBook-Pro-2:git-present kmchale$
```