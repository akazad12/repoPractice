## Creating a new repo:
1. 'git init' <- Initializing a git repsitiory
2. Create repo on github
3. 'git remote add origin <github http url>'
4. To test run 'git remote -v' shows if remote reposiitory is connected


>## How to create / push commits
1. 'git add .' - means git add everything, all saved changes
2. 'git commit - m "commit message here"'
3. 'git push origin main/master' or 'git push origin main/master -u'

*** If you use '-u' upstream flag, all subsequent/further commit you use 'git push' instead of 'git push origin main'

# Branching your repo:
1. 'git branch <name of new branch>' - create a new branch
2. 'git checkout' to see what branch we are on
3. 'git checkout <name of branch>',  - to swith to different branch
  - when in alternative branch all chanbes are saved commited only to that branch

  *** DO NOT MAKE CHANGES TO BOTH BRANCHES***
## Git Merging
- Merging is the process of comining a secondary branch with the main/master branch
1. Swith to branch you want to merge into (usually main branch)
2. 'git merge <name of branch to merge>' -combines secondayr branch into main

