# gekresto

Restoku Restomu, Sayangku hanya untukmu

#Basic Code

1. Fork https://github.com/WawanAndiika/taskmanager.git
2. Do this bash

 ```bash
    > git clone https://github.com/[username]/taskmanager.git
	> cd gekresto/
	> git init
	> git config --global user.name "[username]"
	> git config --global user.email "[your@email.com]"
    > git remote set-url origin https://github.com/[username]/taskmanager.git
    > git remote add upstream https://github.com/WawanAndiika/taskmanager.git
    > git remote -v 
 ```

3. Update Workflow
    - do git push to your repository
    - create pull request
    - after succeed do this bash
    - first push your directory do this bash
    > git add *
	> git commit -am "Add new directory [username]"
	> git push origin master

```bash
    > git fetch upstream
    > git merge upstream/master
 ```
