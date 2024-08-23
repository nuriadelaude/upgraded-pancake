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

# MarkDown 101

A little theory that seems useful to me about MarkDown

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

# MarkDown in depth

## Tables
Tables allow you to organize data in a tabular format. You define headers and rows using pipes `|` and separate the header from the body using dashes `-`.

**Example:**

```markdown
| Header 1 | Header 2 |
|----------|----------|
| Row 1    | Data     |
| Row 2    | More Data|

```

## Fenced Code Blocks

Fenced code blocks allow you to display code in a formatted way. Wrap your code in triple backticks. Optionally, specify a language for syntax highlighting.

```python
print("Hello, World!")
```

## Heading ID
You can assign custom IDs to headings for easier linking within the document. Simply add `{#custom-id}` after the heading text.

## This is a Heading {1}

## Footnote
Footnotes allow you to provide additional context or references at the bottom of your document. You place the reference inline, and the footnote itself is defined at the bottom.

Here's a sentence with a footnote.[^1]

## Definition List
Definition lists let you create a list of terms with their definitions. Use a colon `:` to separate the term from its definition.

Term 1
: Definition of term 1

Term 2
: Definition of term 2

## Strikethrough

Strikethrough allows you to cross out text. Wrap your text with double tildes `~~` to achieve this effect.

~~This text is crossed out~~

## Highlight
Highlight text by wrapping it in double equal signs `==`.

This is ==highlighted text==.

## Task List
Task lists are useful for tracking progress in a checklist format. Use `- [ ]` for unchecked items and `- [x]` for checked items.

- [x] Task 1
- [ ] Task 2
- [ ] Task 3

## Emoji
You can add emojis by typing their shortcodes, wrapped in colons `:`. The rendered emoji will appear in your text.

:smile: :rocket:

## Subscript
Subscript text can be created using the `<sub>` HTML tag.

This is H<sub>2</sub>O.

## Superscript
Superscript text can be created using the `<sup>` HTML tag.
 
This is E = mc<sup>2</sup>.

[^1]: This is the footnote.




