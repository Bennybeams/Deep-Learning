# Steps taken in UBISea project with DSTI

## GIT

- Create a local repository with a readme and .gitignore on GitHub
- Set it as working directory (move into it)
- git clone it locally with : git clone https://github.com/Bennybeams/<repositoryname>.git
- checkout the branch with git checkout -b develop. New branch is locally created and we move on it.
- add the files of the local repository.
- do a git status to check the repository. New files should be highlighted.
- add files to local staging area with git add .
- commit the file with git commit "comment" (comment may also be made by vim)
- then push the comitted files with command  git push --set-upstream origin deep_learning_branch
- new files should be now visible in the new branch in the repository