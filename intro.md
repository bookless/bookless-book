# Introduction

## Motivation

Writing a book is hard. It's harder if we don't have a powerful enough tool for it.

### Distraction-free mode

When onto writing something, I want to turn on the full focus mode. Concentrate only to what I am thinking and writing at the moment. Nothing else. That the first thing I want when creating Bookless: the distraction-free mode.

### Chapters explorer

There is rarely anyone who are writing a one-chapter book. I love to organize things for the sake of self-sanity. So my book should be divided into chapters. That the second things Bookless must have: the chapters explorer.

### Local plain text files

Plain text files are kings. Of course they are! Not every computers come with a pre-installed expensive Microsoft Word. But I assure you, every single one can edit a plain text file! So Bookless book's chapters are, not very surprisingly, just plain text files on your computer.

### Nice by default

Every book should be beautifully formatted. That's not even for debate. But not every one can do that. So Bookless should come with some nice-looking pre-defined templates so every authors can just really get started quickly.

## Get started

Just download Bookless from its [GitHub][bookless-source], and then install it to your computer. Get started with 3 simple steps:

- Open the Bookless app
- Choose a folder to working on
- Create a new file and start writing

## Usage

### Chapters explorer

A typical book contain many chapters. They will be displayed on your left bar. Click the bookmark icon to expand it if it's hidden. Click again to enter focus mode. You can double click on the top area to toggle the mode if you like.

All chapters belong to the book will be shown on the left. You can drag and drop to re-order them. Each chapter is a Markdown file on your choosen working folder. You can rename or delete them as you see fit. Just be aware that the delete action is permanent, there is no recycle bin for you to look for deleted files.

### Chapter content

Each chapter file must start immediately with the chapter title using the first-level heading, e.g., `# Chapter Title`. All Markdown files must be encoded in UTF-8, especially when they contain multi-byte characters such as Chinese, Japanese, and Korean. Here is an example (the bullets are the filenames, followed by the file content):

- preface.md

    ```markdown
    # Preface {-}
    
    In this book, we will introduce an interesting
    method.
    ```

- intro.md

    ```markdown
    # Introduction
    
    This chapter is an overview of the methods that
    we propose to solve an **important problem**.
    ```

- method.md

    ```markdown
    # Methods
    
    We describe our methods in this chapter.
    ```

- application.md

    ```markdown
    # Applications
    
    Some _significant_ applications are demonstrated
    in this chapter.
    
    ## Example one
    
    ## Example two
    ```

- summary.md

    ```markdown
    # Final Words
    
    We have finished a nice book.
    ```

The content are automatically saved so you don't have to. You should put your book on a backup system like Dropbox or iCloud to prevent any unwanted accident that may happen to your computer.