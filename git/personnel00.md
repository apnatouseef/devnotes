`git add <filename>` .... it will add file into git then git will start to track that file.
`git status` ... it will show current status of file (its added or not, changes commited or not).
`git commit -m "this commited"` ... this will commit the changes.
`git diff` ... it will show difference of file changes that not commited yet.

git log ... it will show all previous commits details 

### Git Basic Commands

1. `git add <filename>` – Adds the file to Git (Git starts tracking it).
2. `git status` – Shows current status (added, modified, staged).
3. `git commit -m "this is my commit"` – Commits the changes with a message.
4. `git diff` – Shows the difference between working directory and staged/committed changes.
5. `git log` – Displays a history of all previous commits.

**Interview-Q**

**Q: What is the Git workflow used in your organization?**

A:  
`git add` && `git commit -m "this is my commit"` && `git push`

`git clone url`  - it will pull repository from github to our local machine.

**Interview-Q**

🔄 **git clone vs git fork**

✅ `git clone`
- Downloads the **entire repository** (code, history, branches) to your **local machine**.
- Commonly used when you want to **work on someone else's repo directly** or contribute via branches.

git clone https://github.com/username/project.git

✅ `git fork`

* Creates a **copy of someone else's repository** under **your own GitHub account**.
* Used when you want to **contribute to someone else's project** without affecting the original repo.
* After forking, you can `git clone` your **forked repo** to your local system.

📌 Steps:

1. Click **Fork** button on GitHub
2. Clone your fork:

** Git Branches**
git branch   it will show current branch
git checkout -b newbranch1    it will create and switch to this new branch

vim and add calculator.sh file 
git add filename
git commit -m "this is from my side"
git status
git log
git log --oneline    it will show logs in oneline

user001@test-kube:~/git-practice$ git log
commit 42db81800eaa111f63baaae4d8d96572aadbeb4c (HEAD -> newbra1)
Author: Ali Khan <ali.khan@example.com>
Date:   Fri Jun 20 01:44:17 2025 +0000

    new change2

commit aee2915a23706608985cb766bf408c846a251f87 (main)
Author: Ali Khan <ali.khan@example.com>
Date:   Wed Jun 18 02:39:20 2025 +0000

    next change

commit 0e393029500f236fc03085cfa72036c0f167e314
Author: Ali Khan <ali.khan@example.com>
Date:   Fri Jun 13 02:59:10 2025 +0000

    this is my change

git checkout main     it will switch to main branch

Now Three new thisgs (git merge git rebase git cherry-pick)

