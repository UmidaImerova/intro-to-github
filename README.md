### Intro to GitHub

RESET A last commit

- git reset HEAD~ // this will delete the commit from local repo.
- git push origin main -f // this will force push all your changes from local to remote.

Day to day work: this is the normal flow - for pushing changes from local to remote

- git pull origin BRANCH_NAME - to avoid conflicts
- Add specific file to stage - git add <FILE_NAME> or git add .
- commit those files to local repo - git commit -m 'COMMIT MESSAGE GO HERE'
- then push those changes to remote repo/branch - git push origin BRANCH_NAME
- hsdhdgvcdhgj
  /// What the pull reaquest will do? - done on main branch
- git fetch // on main
- git merge BRNACH_NAME (from where we have created a pull request)// darsh-feature-1
- git push origin main

- git pull = git fetch + git merge
