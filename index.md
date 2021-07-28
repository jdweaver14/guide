* TOC
{:toc}

# Getting Started

## Creating a GitHub Account

If you don’t already have one, you will need a GitHub account to get started with your GitHub hosted Digital Portfolio.
Test <a href="page1.md">Page 2</a>

## Creating a New Repo

Once logged into your GitHub account, you will need to create a new repository with the following steps.
1. Create a new repository
![Creating a New Repo GIF](https://user-images.githubusercontent.com/22283357/126868712-9e824e2d-270d-4302-9b9a-158ba2a476fa.gif)

2. Create an index.md (markdown) file in your repository and commit
![Adding Firsg File GIF](https://user-images.githubusercontent.com/22283357/126868743-39709a5f-090d-44c3-bd6c-364f3ecfde14.gif)

## Linking Your Repo to GitHub Pages

1. In Settings > Pages, set up your repo to publish
![Publishing to GitHub Pages GIF](https://user-images.githubusercontent.com/22283357/126868848-45a19ed9-3e25-49e2-a065-3f95a6110a23.gif)

2. Choose a theme for your site
![Selecting A Theme GIF](https://user-images.githubusercontent.com/22283357/126868961-43d3fead-8fd3-4cad-b825-8feac8612e1f.gif)

3. Commit - your site is now online
![Commit the Template File GIF](https://user-images.githubusercontent.com/22283357/126868764-7118795c-2416-48f5-a59b-efc289690974.gif)

4. You can edit the code in index.md to customize text, add images
![Viewing Your Page GIF](https://user-images.githubusercontent.com/22283357/126868853-cd5e5ad2-b131-4319-837d-93adffbc4589.gif)


## Editing Pages

Your GitHub page can be edited in Markdown, a lightweight markup language. If you are unsure how to format or add content, you can search on their [website](https://www.markdownguide.org/)


# Markdown Cheat Sheet

## Formatting Text
### Headings
In Markdown, you can use Heading Styles with a number of # symbols, followed by a space.
Example:
  # The text here will be in style Heading 1
# The text here will be in style Heading 1
  ## The text here will be in style Heading 2
## The text here will be in style Heading 2

  **bold text here**
**bold text here**
  *italic text here*
*italic text here*
  ***bold and italic text here***
***bold and italic text here***

### Bullet Points
Use - to denote a bullet point
  - point a
  - point b
  - point c
- point a
- point b
- point c

Blockquotes
Text can be put into a block quote section by beginning the line with the > symbol followed by a space.
> the text here will be in a block quotes

You can create multiline, and nested blockquote sections

> 
> 
>>
>

### Code Blocks
If you indent code sections with a tab, they will appear as a codeblock in markdown.





## Links and Images
### Clickable links
<https://www.markdownguide.org>
<fake@example.com>


### Adding a link to text
The word in square brackets will be linked to the address in brackets. The words in quotation marks are the title - they will appear when you hover over the link.
Click [Here](https://www.engineering.cornell.edu/)
My favorite search engine is [Google](https://www.google.com "The best search engine")

### Adding Images:
The text in quotation marks is the (optional) title - it will appear when the link is hovered over. The text in brackets is not displayed.
![The San Juan Mountains are beautiful!](/assets/images/san-juan-mountains.jpg "San Juan Mountains")
//insert screenshot / gif 
Adding Videos:
The text in quotation marks is the (optional) title - it will appear when the link is hovered over
![The San Juan Mountains are beautiful!](/assets/videos/san-juan-mountains.gif "San Juan Mountains")
//insert screenshot / gif 

## Troubleshooting
If you need to escape a character, you can use backslash (e.g. if you want to write a number followed by a ‘.’, to prevent it from being detected as a numbered list).

You can also use HTML in your markdown file between tags
For example:
 This <em>word</em> is italic. 
Would produce the same effect as:
This *word* is italic.



