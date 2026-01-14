## NOTE FOR WORKING WITH GIT 

```BASH

gh auth login 
gh auth status

gh repo create foundation-g5-sharing-aft --public
 https://github.com/keoKAY/foundation-g5-sharing-aft



cd inside-your-folder
git init 
git remote add origin https://github.com/keoKAY/foundation-g5-sharing-aft

git remote -v # to show the origin 
git add . 

git config --global credential.helper store
git config --global user.email "your-email@example.com"
git config --global user.name "james"
git commit -m "first commit " 
git push -u origin master 
```