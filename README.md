# git-cmds
A small guide to most used git cmds

`$ git config --global user.name "Danny Adams"`

`$ git config --global user.email "myemail@gmail.com"`

`$ git init <directory>`

`$ git clone <url>`

`$ git add <file>`

`$ git add .`

`$ git commit -m "commit message"`

```
main: default development branch
origin: default upstream repo
HEAD: current branch
HEAD^: parent of HEAD
HEAD~4: great-great grandparent of HEAD
```

`$ git branch`

`$ git branch <new-branch>`

`$ git checkout <branch>`

`$ git checkout -b <newbranch>`

`$ git branch -D <branch>`

```
 $ git checkout b
 $ git merge a
```

`$ git merge --squash a`

```
$ git checkout feature

$ git rebase main
```

```
$ git remote add <alias> <url>
```

```
git checkout main
git pull
git checkout my-feature-branch
git merge main
```
```
git checkout main
git pull upstream main
git checkout my-feature-branch
git rebase main
```
-----------------------------------------------------------------------------------------------------------------------------------------

**Common Questions** 🤔:

What is Version Control? 🕒
Version control helps manage changes to software code over time. It tracks modifications, enables collaboration, and provides a history of development.
-----------------------------------------------------------------------------------------------------------------------------------------
Why Use Version Control? 🤝
Version control streamlines teamwork, reduces errors, helps track changes, and provides a safety net for code experimentation.
-----------------------------------------------------------------------------------------------------------------------------------------
What is Git? 🐙
Git is a distributed version control system. It tracks code changes, enables collaboration, and maintains a history of commits.
-----------------------------------------------------------------------------------------------------------------------------------------
How Does Git Work? 🔄
Git creates snapshots of your code over time. Each snapshot represents a commit containing changes, and branches allow for parallel development.
-----------------------------------------------------------------------------------------------------------------------------------------
What is GitHub? 🌐
GitHub is an online platform that hosts Git repositories. It offers collaboration tools, issue tracking, and a space for developers to showcase projects.
-----------------------------------------------------------------------------------------------------------------------------------------
What is a Repository? 📁
A repository (repo) is a directory that contains your project files and their history. It's where your codebase lives.
-----------------------------------------------------------------------------------------------------------------------------------------
What is a Commit? 📝
A commit is a saved change to your codebase. It captures modifications and provides a snapshot of your project at that moment.
-----------------------------------------------------------------------------------------------------------------------------------------
What is a Branch? 🌿
A branch is a separate line of development in Git. It allows developers to work on features or fixes without affecting the main codebase.
-----------------------------------------------------------------------------------------------------------------------------------------
How to Collaborate on GitHub? 👥
GitHub facilitates collaboration through features like pull requests, issue tracking, and code reviews. Developers can contribute to projects seamlessly.
-----------------------------------------------------------------------------------------------------------------------------------------
What is a Pull Request? 🛎️
A pull request is a way to propose changes from a forked repository to the original repository. It enables collaboration and code review.
-----------------------------------------------------------------------------------------------------------------------------------------
What is Forking? 🍴
Forking is creating a personal copy of a repository. It allows you to experiment, make changes, and contribute back to the original project.
-----------------------------------------------------------------------------------------------------------------------------------------
How to Resolve Merge Conflicts? ⚔️
Merge conflicts occur when Git can't automatically reconcile changes. Developers need to manually resolve conflicts before merging branches.
-----------------------------------------------------------------------------------------------------------------------------------------
How Does Git Handle Large Files? 📦
Git's default behavior isn't ideal for large files. Git LFS (Large File Storage) or specialized hosting services are used to manage large assets.
-----------------------------------------------------------------------------------------------------------------------------------------
What is .gitignore? 🚫
.gitignore is a file that specifies which files and directories should be excluded from version control, helping to keep the repository clean.
-----------------------------------------------------------------------------------------------------------------------------------------
What is Continuous Integration/Continuous Deployment (CI/CD)? 🔄🚀
CI/CD is a practice where code changes are automatically built, tested, and deployed to production. It ensures frequent and reliable software releases.
-----------------------------------------------------------------------------------------------------------------------------------------
Feel free to dive deeper into these questions to gain a solid understanding of version control, Git, GitHub, and software development practices! 🌟👩‍💻👨‍💻

Feel free to fork 🍴this 👨‍🍳 simple Angular code into your GitHub account click here. Take a peek and if you fancy it, go ahead and star the repository. Happy coding! 🤝
-----------------------------------------------------------------------------------------------------------------------------------------
