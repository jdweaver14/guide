---
title: Markdown Cheatsheet
layout: template
filename: markdowncheatsheet
--- 

* TOC
{:toc}

# Markdown Cheat Sheet

## Formatting Text
### Headings
In Markdown, you can use Heading Styles with a number of # symbols, followed by a space.
Example:
```
### The text here will be rendered in style Heading 1
```
> ### Heading 3



```
## The text here will be rendered in style Heading 2
```
> ## Heading 2



```
**bold text here**
```
> **bold text here**



```
*italic text here*
```
> *italic text here*



```
***bold and italic text here***
```
> ***bold and italic text here***


### Bullet Points
Use - to denote a bullet point
```
  - point a
  - point b
  - point c
```
- point a
- point b
- point c

### Blockquotes
Text can be put into a block quote section by beginning the line with the > symbol followed by a space.

```
> the text here will render in a block quotes
```
> this is how text in block quotes will appear

You can create multiline, and nested blockquote sections by using  > vs >>
```
> level 1
> level 1
>> level 2
```
> level 1
> level 1
>> level 2


### Code Blocks
If you indent code sections with a tab, they will appear as a codeblock in markdown.
You can also separate them by using three backticks before and after the code section




## Links and Images
### Clickable Links
```
<https://www.markdownguide.org>
<fake@example.com>
```


### Adding a link to text
The word in square brackets will be linked to the address in brackets. The words in quotation marks are the title - they will appear when you hover over the link.
```
Click [Here](https://www.engineering.cornell.edu/ "Cornell Engineering")
```
Click [Here](https://www.engineering.cornell.edu/)
My favorite search engine is [Google](https://www.google.com "The best search engine")

### Adding Images
The text in quotation marks is the (optional) title - it will appear when the link is hovered over. The text in brackets is not displayed.
```
![The Cornell Campus!](https://www.cornell.edu/about/img/main-Tower1.Still001-720x.jpg "Cornell Campus")
```
![The Cornell Campus!](https://www.cornell.edu/about/img/main-Tower1.Still001-720x.jpg "Cornell Campus")

### Adding Videos
You can add videos with HTML, see code snippet here:
```
<video width="320" height="240" controls>
  <source type="video/mp4" src="https://cuauv.org/static/media/CUAUV%20Hero%20Video.64b4eaf3.mp4">
</video>
```
<video width="320" height="240" controls>
  <source type="video/mp4" src="https://cuauv.org/static/media/CUAUV%20Hero%20Video.64b4eaf3.mp4">
</video>


## Troubleshooting
If you need to escape a character, you can use backslash (e.g. if you want to write a number followed by a ‘.’, to prevent it from being detected as a numbered list).

You can also use HTML in your markdown file between tags
For example:
```
This <em>word</em> is italic. 
```
Would produce the same effect as:
```
This *word* is italic.
```
> This *word* is italic.

If you are unsure how to format or add content, and need more info on Markdown you can search on their [website](https://www.markdownguide.org/)

