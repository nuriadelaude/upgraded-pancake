# GitHub Certification - Foundationals

Hi there, this is a repo I'll be using to test a few things for the certification. Also, here are a few steps on how I created this repository.

> Please bear in mind that English is not my first language, so there may be some errors. Please be kind.

Before anything else, we need to set up the configurations in 

```sh
git config --global user.name "your-username"
git config --global user.email "your-email@example.com"
```

First, we will have to initialize the repo using `git` commands.

```sh
cd <the-desired-folder>
git init 
git add . 
git status
git commit -am "message"
git branch -m main
git remote add origin https://github.com/nuriadelaude/upgraded-pancake.git
git push -u origin main
```

## How to change branches

To create one we have to use:

```sh
git branch <branchname>
```

To switch branches we can use:

```sh
git checkout <branchname>
```

To list all of our branches:

```sh
git branch
```
