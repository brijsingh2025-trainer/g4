…or create a new repository on the command line
echo "# g6" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/brijsingh2025-trainer/g6.git
git push -u origin main
…or push an existing repository from the command line
git remote add origin https://github.com/brijsingh2025-trainer/g6.git
git branch -M main
git push -u origin 









// Basic command we discussed 
  -- clone
  -- initialization - git init
  -- git status   -- to check status of current repo
  -- git add --all -- it is for add all files existing into current repo
  -- git add filename --> in this case only specified file will be added
  -- git checkout -b branchname -- it is created new branch from current branch
  -- git push origin branchname -- it is push branch over repo


  // cherry-pick 
    git cherry-pick 16c1958ed23a8eed84e44e15275275f2cbae5809 








