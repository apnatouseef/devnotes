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

