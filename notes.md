# Markdown

## Content Management
Hugo natively supports Markdown and Emacs Org-Mode, but there are additional formats such as asciidoc that are supported via external helpers

## Introduction to Markdown

- Markdown is a relatively new syntax. Developed in 2004 by John Gruber, markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As John Gruber writes on the Markdown site:

> The overriding design goal for Markdown's formatting syntax is to make it as readable as possible. 
> The idea is that a Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions.

- Plain text files have many advantages over other formats. For one, they are readable on virtually all devices, easy to understand and durable
- By following Markdown syntax, you’ll be able to produce files that are both legible in plain text and ready to be styled on other platforms. Many blogging engines, static site generators, and sites like GitHub also support Markdown, and will render these files into HTML for display on the web. Additionally, tools like Pandoc can convert files into and out of Markdown.
- Markdown files are saved with the extension .md, and can be opened in a text editor such as TextEdit, Notepad, Sublime Text, or Vim.


- Many websites and publishing platforms also offer web-based editors and/or extensions for entering text using Markdown syntax.


- In this tutorial, we’ll be practicing Markdown syntax in the browser using Dillinger, dillinger.io. You’ll be able to enter Markdown-formatted text on the left and immediately see the rendered version alongside it on the right.

- open existing markdown file from github

You’ll notice that while the right panel features a more elegant rendering of the text, the original Markdown file on the left is still fairly readable.

Now, let’s dive into the lesson by writing our own Markdown syntax. Create a new document in StackEdit by clicking the folder icon in the upper right and choosing New document. You may enter a title for the document in the textbox on the top of the page.

### Markdown Syntax

#### Headings

Use the hash symbol, #

#### Paragraphs & Line Breaks

Try typing the following sentence into a Github .md file:

```
Hello!

Today we'll be learning about Markdown syntax.
This sentence is separated by a single line break from the preceding one.
```

This renders as:

Hello!

Today we’ll be learning about Markdown syntax. This sentence is separated by a single line break from the preceding one.

Paragraphs must be separated by an empty line. Leave an empty line between syntax. and This to see how this works. In some implementations of Markdown, single line breaks must also be indicated with two empty spaces at the end of each line. This is unnecessary in the GitHub Flavored Markdown variant that StackEdit uses by default.

#### Emphasis

#### Lists

#### Snippets

#### Links

#### Images

#### Tables

Use http://stevecat.net/table-magic/# to make easy markdown tables!


### Hugo

- In Hugo, you would name your files as ```*.md``` or set markup="markdown" in front matter.

## Resources

### Markdown Cheatsheet

- https://www.markdownguide.org/cheat-sheet

### Web Tools Comparison:

| Stackedit                                                             | Dillinger                                   | Prose                               |
|-----------------------------------------------------------------------|---------------------------------------------|-------------------------------------|
| Sync from Github - navigate to locate files                           | Sync from Github - navigate to locate files | More closely integrated with github |
| Automatic commit message from Stackedit                               | Add your own commit message                 | Add your own commit message         |
| Messes with your markdown: Adds extra Stackedit comment into markdown | No tampering                                | No tampering                        |

### Tutorials

- The really good Markdown tutorial that we adapted by Sarah Simpkin https://programminghistorian.org/lessons/getting-started-with-markdown

### Hugo Exercises

* 7 exercises in 45 minutes, about 5 minutes per exercise but it's really go at your own pace
* Instead of going through together a se of instructions of things you can do with Hugo, we're going to take a less traditional format of independent learning, the same way that you might have to figure out a new technology on your own time, but benefitting from other people around to help you
* We'll provide minimal written/verbal instruction. We encourage you to read the Hugo documentation and google/duckduckgo for help!
* If you have questions, ask your neighbour. [Coding learning is social](https://andromedayelton.com/2013/11/25/reflecting-on-introduction-to-python-for-librarians/). If there's still any remaining questions, put up a stickie and one of us will come and help out
* We're going to take up the exercises after 10, 20, and 45 minutes.
* When we take up the exercises, We're going to ask you:
   * Show us how you worked through the problem. What resources did you consult?
   * Provide everyone with a line by line walkthrough of the answer
   * What problems did you run into along the way? Talk about the tiny mistakes you might have made along the way, things like syntax errors, formatting issues, and so on.

#### Exercise 1

Add a new Portfolio page. Create it as a draft. Then, publish it.

#### Exercise 2

10 minute mark: Take up 1, 2

#### Exercise 3

Create and edit the Archetype for Portfolio. Archetypes are the 

https://gohugo.io/content-management/archetypes/

#### Exercise 4

Add an Archetype for Testimonials

20 minute mark: Take up 3, 4

#### Exercise 5

Custom CSS

Play around with the styling of the site. Under /static/css there is a custom.css file that you can use to override css template files.

1. Change the theme style option to 'pink'
2. Change the "Good Dogs" title in the sidebar to 36px and a different colour
3. Add a box shadow to each dog portfolio image


#### Exercise 6

Custom CSS - overriding existing fonts with web fonts 

Grab a couple of fonts from [Google Fonts](https://fonts.google.com/) and use them to override the fonts on your website. You'll want to edit just the title and body of each dog portfolio post.

#### Exercise 7

Image Metadata - 

45 minute mark: Take up 5, 6, 7
