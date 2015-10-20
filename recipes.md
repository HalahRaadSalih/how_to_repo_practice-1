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
```

### Help someone else with their code
Firstm find the code on github that you want to contribute to.

Then fork it

```shell
$git clone git@github.com:<your username>/<repo name>.git
```
Then, make some changes you think are important.

```shell
$ git add <your files>
$ git commit m- "A really thourough explanation of what we did since this is someone else's work"
$ git push origin master (git clone does the init so no need to type that out in the terminal)
``` 
Finish what you started working on, then push up any additional commits.


File a pull request with the commits in them that you want to share. Make sure you ahve a good explanation in the pull request of what this is, what it's intended to do, and some nice language, rather tham making fun of the original author.


### How to work on two different things at the same time.


###typical collabration patters

A typical collcabration pattern is to actually to fork nd then branch off matser,  then push to your fork then file a pull request. 

The reason fot is  that master, as a branch, should always represent code or whatever that 'works'
 an dis suitable for deployment or sharing ir whatever going on.
