# Hello

This is my project.

## Git process

1. Before you use git, you have to initialize it.

You can use 'git init' to create a local git repo.

2. Before you can commit files you have to stage them. This means selecting the files you want to commit.

You can use 'git add filepath' to stage the file(s) at the filepath.

Staging a folder will stage all files inside it.

3. To commit the staged files, we use 'git commit'. Every commit needs a corresponding message. We can use 'git commit -m "message"' to specify a message for the commit.

## Syncing with coworkers

Git collaboration is don by connectiong a remote repository and pushing (uploading changes) and pulling from (downloading changes) it.

'git push' to push your local commits to the remote.

'git pull' to pull remote commits to local.

## Remote setup

You can configure a remote connection to github using the gh cli

To create a repo from the localgit repo, you can use:
'gh repo create' along with the flags:
'--source=.' to specify that the current folder will be used.
'--private'/'--public' to specify if the repo is publicly accessible.
And '--push' to immediatly push local commits and verify that connections works.

## Merge Conflicts

Git is not a complete project management tool.

Changes may be duplicated.