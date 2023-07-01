---
id: yexc9x2miwhbe6whhceixcu
title: Test2
desc: ''
updated: 1688219420644
created: 1688219420644
---


## Task List   
- [ ] not started
- [w] work in progress
- [x] done
- [?] feedback
- [>] postponed

## Tasks
- [x] Understand Dendron and go through its wiki
- [x] Setup Templates for most of the occurrences
- [x] Build Tutorials based on the templates
- [x] Run it parallel with Joplin for a week  


[reddit_markdown-reference](https://www.reddit.com/wiki/markdown/)

## Markdown Syntax Guide 

### Headers
# This is an h1 tag
## This is an h2 tag
### This is an h3 tag
#### This is an  h4 tag
##### This is an h5 tag
###### This is an h6 tag


### Emphasis
*This text will be italic*

_This will also be italic_

**This text will be bold**

__This will also be bold__

_You **can** combine them_

~~This text will be strikethrough~~


### Lists
#### UNORDERED LIST
- Item 1
- Item 2
  - Item 2a
  - Item 2b
#### ORDERED LIST
1. Item 1
2. Item 2
3. Item 3
   1. Item 3a
   2. Item 3b

#### DEFINITION LIST
Item 1 
: Definition for Item 1

Item 2 
~ Definition for Item 2
~ Another definition for Item 2, with a [link](http://www.example.com)

####Images
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)

### Blockquote
As Kanye West said:

> We're living the future so 
> the present is our past.

### Horizontal Rule
Three or more...

Hyphens, Asterisks, Underscores

---
***
___

### Inline code
I think you should use an
`<addr>` element here instead.


### Fenced code block

```ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```



### Tables
| First Header                | Second Header                |
| --------------------------- | ---------------------------- |
| Content from cell 1         | Content from cell 2          |
| Content in the first column | Content in the second column |

### Abbreviation
The HTML specification

*[HTML]: Hyper Text Markup Language
*[W3C]: World Wide Web Consortium
The HTML specification
is maintained by the W3C.


### Footnotes
Content [^1]

[^1]: Hi! This is a footnote


### Frontmatter Variable Substitution

this note is in it's {{ fm.stage }} stage

Created: {{ fm.created }}

Updated: {{ fm.updated }}

Title : {{ fm.title }}

Description: {{fm.desc }}


### Diagrams
```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
Root
    A
      B
      C
```
### Folding
You can create special folded sections with the below syntax.

<details>
  <summary>Click to expand!</summary>

  ## Heading
  1. A numbered
  2. list
     * With some
     * Sub bullets
</details>
