# Gym-Git-Exercise-Solutions
## Bundle 1
### Exercise 1
```Bash
 898  mkdir TheGymExercise
  899  cd TheGymExercise
  900  git init
  901  git branch
  902  git branch --show-current
  903  git branch -m master main
  904  touch index.html
  905  touch index.css
  906  touch style.js
  907  git status
  908  mv index.css styles css
  909  mv index.css styles.css
  910  mv index.js styles.js
  911  mv index.js style..js
  912  ls
  913  git add .
  914  git status
  915  clear
  916  git commit -m "created  files"
  917  git status
  918  clear
  919  git remote add origin https://github.com/brendahuwitonze/TheGymeEXercise.git
  920  git push origin main
  921  index.html code
  922  index.html 'code'
  923  git branch dev
  924  git checkout dev
  925  git branch test
  926  git branch
  927  git branch -d test
```
 ### Exercise 2
```Bash
  928  touch home.html
  929  git branch
  930  git stash push -m "the home page"
  931  git status
  932  git add home.html
  933  git stash push -m "saving the home file"
  934  git branch
  935  git status
  936  touch about.html
  937  git status
  938  git add about.html
  939  git stash push -m "the about file"
  940  touch team.html
  941  git add team.html
  942  git stash push -m "saved the team file"
  943  stash git stash pop
  944  git stash pop
  945  git status
  946  git stash push -m "saved the team file"
  947  git status
  948  git stash pop
  949  git stash list 
  950  git stash push -m "saved the team file"
  951  git stash list
  952  git stash pop 1
  953  git stash list
  954  git stash pop 1
  955  git stash list
  956  git stash pop 0
  957  git reset team.html
  958  git status
