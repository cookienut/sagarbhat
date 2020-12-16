---
layout: post
title:  Markdown Cheat Sheet
categories: [Markdown,HTML]
excerpt: A quick reference to the Markdown syntax to get the best out of Markdown. This guide will be beneficial for writing markdown files or while using Markdown in combination with static site-generators such as Jekyll.
---

This Markdown cheat sheet provides a quick overview of various Markdown syntax elements.

# Basic Syntax

These are the elements outlined in John Gruber’s original design document. All Markdown applications support these elements.

1. Heading : `# HeadingH1` OR `## HeadingH1` OR `### HeadingH3` and so on.
2. Bold :	`**bold text**`
3. Italic : `*italicized text*`
4. Blockquote : `> blockquote`
5. Ordered List:

  ```
  1. First item
  2. Second item
  3. Third item
  ```

Unordered List 	- First item
- Second item
- Third item
Code 	`code`
Horizontal Rule 	---
Link 	[title](https://www.example.com)
Image 	![alt text](image.jpg)
Extended Syntax

These elements extend the basic syntax by adding additional features. Not all Markdown applications support these elements.
Element 	Markdown Syntax
Table 	| Syntax | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |
Fenced Code Block 	```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
Footnote 	Here's a sentence with a footnote. [^1]

[^1]: This is the footnote.
Heading ID 	### My Great Heading {#custom-id}
Definition List 	term
: definition
Strikethrough 	~~The world is flat.~~
Task List 	- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media

For more details: https://www.markdownguide.org/cheat-sheet/
