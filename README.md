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
```
## Bundle 2
### Exercise 1
``` Bash
  904  git branch ft/bundle-2
  905  git checkout ft/bundle-2
  906  git touch service
  907  git add service.htl
  908  git branch
  909  clear
  910  git add service.html
  911  git status
  912  git commit -m "saved changes on the service file"
  913  git push origin master
  914  git push origin main
  915  git push origin ft/bundle-2
  ```

  ## Exercise 2
```bash
943  git branch ft/service-redesign
  944  git checkout ft/service-redesign
  945  touch service.html 
  946  git add .
  947  ls
  948  rm -rfteam.html 
  949  rm team.html
  950  git status
  951  git add service.html
  952  git commit -m "new services"
  953  git push origin ft/service-redesign
  954  git diff
  955  git diff ft/service-redesign main
  956  git merge
  957  git checkout main
  958  git merge
  959  git merge ft/service-redesign
  960  git status
  961  git push origin main
  962  git pull 
  963* 
  964  git checkout ft/service-redesign
  965  git pull main
  966  git pull 1
  967  git pull main
  968  git status
  969  git branch
  970  git checkout main
  971  git pull main
  972  git pull ft/service-redesign
  973  git checkout ft/service-redesign
  974  git pull main
  975  git pull ft/bundle-2
  976  git pull dev
  977  git pull main
  978  git branch
  979  git pull  main
  980  cd git
  981  cd .git
  982  git branch
  983  git checkout ft/bundle-2
  984  git ..
  985  cd ..
  986  git checkout ft/bundle-2
  987  git pull main
  988  git status
  989  git branch
  990  git checkout ft/service-redesign
  991  git merge main
  992  git push origin ft/service-redesign
  993  git checkout main
  994  git status
  995  git fetch
  996  git pull
  997  git push origin main
  998  git remote -v update
  999  git pull
 1000  git pull origin main
 1001  git config pull.rebase false 
 1002  git pull origin main
 1003  git add .
 1004  git commit -m "removed conflicts"
 1005  git push origin main

```
## Bundle 3
### Exrcise 1
``` bash
  897  git status
  898    git cherry-pick
  899   git revert <hash>
  9000  git revert --skip
  9001  git push origin ft/faq-page
  ```
  ### Exercise 2
  ```bash
    905  git checkout ft/faq-page
  906  git checkout -b ft/home-page-redesign
  907  git checkout main
  908  git status
  909  git push origin main
  910  git status
  911  git checkout ft/faq-page
  912  git status
  913  git checkout  ft/home-page-redesign
  914  git status
  915  git pull
  916  git branch
  917  git checkout main
  918  git status
  919  git push origin main
  920  git pull
  921  git pull origin main
  922  git push origin main
  923  git checkout  ft/home-page-redesign
  924  git fetch
  925  git rebaseorign main
  926  git rebase orign main
  927  git rebase main 
  928  git status
  929  git add home.html
  930  git push origin ft/home-page-redesign 
  931  git checkout main
  932  git status
  933  git commit -m "changes on the home file"
  934  git push origin main

  ```
  ## Bundal 4
  ### Exerices 1
  ``` bash
  936  git checkout main
  937  git remote add origin https://github.com/brendahuwitonze/NewGitExercise.git
  938  clear
  939  git remote add git-copy https://github.com/brendahuwitonze/NewGitExercise.git
  940  git status
  941  git add home.html
  942  git commit -m "changes in the homepage"
  943  git push origin main
  944  git push -u -f origin main
  945  git push -u origin main
  946  remote
  947  git remote
  948  git push git-copy
  ```
  ### Exercise 2
  ```bash

  960  git checkout -b ft/squashing
  961  git merge sqaush ft/footer
  962  git status
  963  git branch
  964  git merge --sqaush ft/footer
  965  git merge --squash ft/footer 
  966  git status
  967  git commit -m "footer changes squashing"
  968  git push origin ft/squashing
  ```
  ## Bundle 5
  ### Exercise 2
  ``` bash
  968  git add index.html
  969  git commit -m "made changes to the folked repo"
  970  git branch
  971  git push origin main
  ```
  ### Bundle 6
  ## Exercise 1
  ```bash
   974  git checkout -b menu/branch
  975  touch menu.html
  976  git add .
  977  git status
  978  git commit -m "created a menu file"
  979  git push menu/branch
  980  git branch
  981  git push origin  menu/branch

```
## Exercise 2
```bash
 983  git checkout -b bug/fix
  984  move index-4.html  contact.html
  985  git add contact.html
  986  git commit -m "git changed the file name"
  987  git push origin bug/fix
  988  git branch main
  989  git checkout main
  990  git push origin main
  991  git checkout bug/fix

```
### Exerise 3
```bash
 994  git checkout bug/fix
  995  git add contact.html
  996  git commit -m "made changes on the contact"
  997  git push origin bug/fix