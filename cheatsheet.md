#Git Cheatsheet

### Start a new project

```shell 
$ mkdir project_name
$ git init
$ touch readme.md
$ git add readme.md
$ git commit -m "initial commit"
```
### Do some work and then save it!

```shell
$ git status
$ git add <whatever file>
git status
git commit -m:I made a bunch of changes, there are so many details wee"
```

### Share my work with the world!

First, create a github repo.

```Shell
$ git remote add origin git@github.com:<github username>/<anme of repository>.git
$ git push -u origin master