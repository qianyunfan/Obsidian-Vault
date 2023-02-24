# PREFACE
- To use obsidian better, I learn git again from [创建版本库 - 廖雪峰的官方网站 (liaoxuefeng.com)](https://www.liaoxuefeng.com/wiki/896043488029600/896827951938304) .
# INSTALL

- After download git, should set name and email address.
```
$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"
```

# START
1. Use cd command to a dictionary you want.
2. Input `git init` in cmd, it will make this dictionary become a **repository**, which can record and control all changes by generate **.git** folder.
# Command
- `git add` add file into stage. Just a buffer between repository and work space.
- `git commit -m "xxxxxx"` commit file into repository. The difference with `add` is that add is just _add_ this file, while `commit` means you confirm your changes and put the changed file into repo. `commit` will commit all changed files. After `-m`  is our commit info, like what's the change. 
- `git diff` show differences with local file and added file.
- `git status` show status.
- `git log` show logs. Use `git log --pretty=oneline` show briefly.
- `git reset` means rollback to the previous version. Use HEAD^^^ or HEAD~3 as parameter. Git use HEAD as a pointer to point which is current version.Can also use version code as parameter to reset version.
- `git reflog` show all your options and version code.
- `git checkout`
	1. Add `--filename` as suffix. 
- 