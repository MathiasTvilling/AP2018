[The concept of git in command line and github](http://product.hubspot.com/blog/git-and-github-tutorial-for-beginners)
- [Install git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- Setup git 1: prepare a working directory, then type 
  ```
  git init
  ```
- Setup git 2: 
  ```
  git config --global user.name [Username] 
  ```
- Setup git 3: 
  ```
  git config --global user.email [email address] 
  ```
- Download the github files to local: 
  ```
  git pull https://github.com/siusoon/VocableCode.git
  ```
If the downloaded files different from the local, it will merge with the local. Just input the message and then esc (meaning save) > :wq (meaning exit)
- Sign up: [github account](https://github.com/) and create your own repository "Respositories" > click the "New" button
- Modify your file, add your code files etc
- See cheatsheet [here](https://services.github.com/on-demand/downloads/github-git-cheat-sheet.pdf)
- Example: If you want to remove a file > type rm, and if you want to add file or modify the file > type add
  ```
  git rm filename.extension
  ```
  ```
  git add filename.extension
  ```
- Example continue: 
  ```
  git commit -m [description e.g delete what]
  ```
- Upload the files to github:
  ```
  git push --set-upstream [github with your respository url] master
  ```
- other useful commands:
  ```
  git status
  git diff    //see the difference
  git add *   //staging everything -> then commit -> then push
  ```