# gekresto

Restoku Restomu, Sayangku hanya untukmu

#Basic Code

1. Fork https://github.com/rivalbamen/taskmanager.git
2. Do this bash

 ```bash
    > git clone https://github.com/[username]/taskmanager.git
	> cd taskmanager/
	> git init
	> git config --global user.name "[username]"
	> git config --global user.email "[your@email.com]"
    > git remote set-url origin https://github.com/[username]/taskmanager.git
    > git remote add upstream https://github.com/blidodi/taskmanager.git
    > git remote -v 
	> touch [username]/README.md
	> git status
	> git add [username]
	> git add [username]/README.md
	> git commit -am "Add new directory [username]"
	> git push origin master
 ```

3. Update Workflow
    - do git push to your repository
    - create pull request
    - after succeed do this bash

```bash
    > git fetch upstream
    > git merge upstream/master
 ```
