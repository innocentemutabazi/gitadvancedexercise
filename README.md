# gitadvancedexercise
 # First part
## Exercise 1-5

```bash
2 git log
   3 git log --oneline
   4 git rebase -i HEAD~2
   5 git log --oneline
   6 git rebase -i HEAD~2
   7 git log --oneline
   8 git rebase -i HEAD~4
   9 git rebase -i HEAD~3
  10 git log --oneline
  11 git log
  12 git rebase -i HEAD~1
  13 git status
  14 git reset HEAD^
  15 git status
  16 git add test3.md
  17 git commit -m "Created the thir... 
  18 git add test4.md
  19 git commit -m "created the four... 
  20 git rebase --continue
  21 git log --oneline
  22 git rebase --i HEAD~1
  23 git rebase -i HEAD2
  24 git rebase -i HEAD~2
  25 git log --oneline
  26 git rebase -i HEAD1
  27 git rebase -i HEAD~1
  28 git log --oneline\
  29 git log --oneline
```
## Exercise 6

```bash
 33 git add unwanted.txt
  34 git commit -m "Unwanted commit"    
  35 git rebase -i HEAD~1
  36 git rebase -i
  37 git log --oneline
  38 git rebase -i HEAD~2
  39 git log --oneline

  ```
  ## Exercise 7
  ```bash
    36 git rebase -i
  37 git log --oneline
  38 git rebase -i HEAD~2
  39 git log --oneline
  ```
 ## Exercise 8
 ```bash
   40 git branch ft/branch
  41 git checkout -b ft/branc
  42 git branch -d ft/branc -d
  43 git checkout main
  44 git branch -d ft/branc -d
  45 git checkout -b ft/branch
  46 git checkout ft/branch
  47 git add test5.md
  48 git commit -m "Implemented test 5" 
  49 git log
  50 git log --oneline
  51 git checkout main
  52 git cherry-pick f132caf
  53 git status
  54 git log --oneline

```
  ## Exercise 9
```bash
  55 git log --graph
```
  ## Exercise 10
```bash
  56 git reflog
```