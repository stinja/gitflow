# gitflow
A page describing a git workflow for junior developers looking to keep their github updated with all their learning projects.

## Quick Facts

Some basic Git commands are:
```
git status
git add
git commit
```

You can find lots of pretty inforgraphics for quick reference if you do an image search for "git commands cheat sheet"

[import existing repository](https://docs.github.com/en/get-started/importing-your-projects-to-github/importing-source-code-to-github/adding-locally-hosted-code-to-github)
[Create a new repository](https://docs.github.com/en/get-started/quickstart/create-a-repo)


## Preparation

- Open up your IDE
- Open a project or create a new one
- Make sure the project you have open has a `.git` folder in the root directory
- Direct terminal to correct directory. (`pwd` to check current directory, `cd <path>` to change to project directory)


## Flow

- If existing project already on github AND local machine go to project root on local and run `git pull <repo>`.
- In terminal run `git status` and read. 
- If git status returns showing no new files or commits, proceed to do work on project.
- Save your work by using `Ctrl` + `S`.
- Reach a stopping point in your work and run `git status` and read.
- If git status returns showing no new files or commits, return to step 3.
- If git status shows list of files run `git add .` to add all files.
- (optional) `git status` again to see that your files have been added to the commit.
- `git commit -m "Describe changes and reasons for commit"`
- `git push`
- Return to step 2.
