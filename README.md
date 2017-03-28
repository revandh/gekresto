# gekresto

Restoku Restomu, Sayangku hanya untukmu

#Basic Code

1. Fork https://github.com/WawanAndiika/gekresto.git
2. Do this bash

 ```bash
    > git clone https://github.com/[username]/gekresto.git
	> cd gekresto/
	> git init
	> git config --global user.name "[username]"
	> git config --global user.email "[your@email.com]"
    > git remote set-url origin https://github.com/[username]/gekresto.git
    > git remote add upstream https://github.com/WawanAndiika/gekresto.git
    > git remote -v 
 ```

3. Update Workflow
    - do git push to your repository
    - create pull request
    - after succeed do this bash
    - first push your directory do this bash
```bash
    > git add *
	> git commit -am "Add new directory [username]"
	> git push origin master
```
	- How to get new update file from other fork
```bash
    > git fetch upstream
    > git merge upstream/master
 ```
