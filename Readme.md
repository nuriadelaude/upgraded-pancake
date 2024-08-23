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

# I'm learning MarkDown
## This is called H2
### This is H3

## Bold, Italic and Block Quote

*italica* is using a single *  at the start and at the end of a line or word

**bold text** is using a double *  at the start and at the end of a line or word

> block quote is using an angle bracket >

## Unordered List
It's Done using a - before the line and it transforms it into a bullet point
- Firts
- Second

## Ordered List

You can use 1. all the way, it will change the numbers auto-magically

1. First
1. Second

## Links

This is done using [] for the title and then the link between () It has to be together

[This is my link](www.linkedin.com)

### Horizontal Rule

This is just 3 hyphens

---

## Code Line

`this is using a backtick`