---
label: Standard Operating Procedures
layout: page
description: SOPs for updating website from PDF.
author:
  - name: Matthew Sung
    email: matthew.sung20@sps.nus.edu.sg
    link: https://sps.nus.edu.sg/user/matthew.sung20/
    avatar: https://sps.nus.edu.sg/wp-content/uploads/ultimatemember/171/profile_photo-190x190.jpg?1658781280
date: 2022-07-27T13:36
---

# Standard Operating Procedures

## Github and You

All files are hosted on Github, then formatted automagically and pushed to Github-Pages. Don't mess with the actions, unless you know what you're doing! This includes the local `.github/actions/` folder.

### Contributing
Please be descriptive when naming commits. It should be styled as such
`[<code><number>] : commit message`

`code`: ADM/C/A/Misc for Administrative, Chapter, Assignment, Miscellaneous

`number`: Self-explanatory
==- Examples

[ADM] for Administrative related issues

[C1] for Chapter (Chapter 1)

[A1] for Assignment 1
===
---

## Formatting
Formatting in this website is done using Retype and Markdown. For documentation, refer to [!badge icon="" text="Retype"](https://retypeapp.org/).

!!!danger Metadata
Whenever possible, add the author and date information when updating documents. This keeps the website in check, and we get to find out which editions errors happen. Do it in the metadata above!

==- Fields
Please refer to Retype's documentation for metadata field information. One thing of note is `order`, which determines the sequence of articles to be shown.

Retype is a little strange, big positive numbers are at the top, small negative numbers are at the bottom. When possible, try to maintain some semblance of structure. Within chapters, use negative indexing to keep the sub-sections in order.


===
!!!

### General Page Arrangement

All chapters should be broken down to the section level! (Ex: 1.2). These will be under the header2 level (`##`).  Subsections will be at header3 (`###`).

Resources for each chapter is located in `/Resources/Chapter n/`. Common resources are to be put in `/Resources/Common/`

No worries, Retype is case-insensitive!



---

## Pushing Changes from PDF

Once in a while, the PDFs get updated and the website has to be updated.
In general, you can copy and paste the .tex file into markdown, and just modify a few elements.

### General fonts

Markdown supports normal, *italics*, and **bold**.


### Elements
Markdown and LaTeX are pretty different in terms of formatting. You will encounter some of these following elements, and changes are to be made as such.

==- Images

The most often thing you'll have to modify are images. In Markdown, images are done by using the reference `![Caption goes here](link to image)`

Do note that absolute referencing should be used when possible, to keep the website functioning nicely. An example of an image addition is as follows:

||| :icon-code: Source
```
![Mike Wazowski, CEO and CFO (Chief Funny Officer) of Monsters, Inc.](/resources/common/mike1.jpg)
```
||| :icon-play: Demo
![Mike Wazowski, CEO and CFO (Chief Funny Officer) of Monsters, Inc.](/resources/common/mike1.jpg)
|||


Occasionally, you'll find text files with spaces. Ew. To make sure links work, keep a set of triangular brackets (<>) around your link.

||| :icon-code: Source
```
![Terrible Link.](</resources/common/mike mask.jpg>)
```
||| :icon-play: Demo
![Terrible Link.](</resources/common/mike mask.jpg>)
|||


==- Links

Links are how they are deployed in Markdown, using the standard [linking](/sops) format.

`[Link text goes here](https://example.com)`

==- Tables

For tables, they're made in Markdown.

I use a [markdown table generator](https://www.tablesgenerator.com/markdown_tables) to make them. They'll look like this.

||| :icon-code: Source
```
| Chapter   | Link                                |
|-----------|-------------------------------------|
| Chapter 1 | Discovering the Universe            |
| Chapter 2 | Falling Apples and Orbiting Planets |
```
||| :icon-play: Demo
| Chapter   | Link                                |
|-----------|-------------------------------------|
| Chapter 1 | Discovering the Universe            |
| Chapter 2 | Falling Apples and Orbiting Planets |
|||

==- Math

Obviously, this module has math.<sup>[[Citation Needed]](https://xkcd.com/285/)</sup> It's imperative then, to keep them visible.

For inline math, for example, $\sin(x)$, use the inline LaTeX method of signifying math.

For blocked math, like
$$
\sum^x_{n=0} x^2
$$

Use the blocked math notation in LaTeX, with $$.

Most of the time, this means you'll just need to find and replace `\[` and `\]` with `$$`

There are some cases where the equal signs are aligned (using `\begin{align*}` blocks.) To get these to work properly, add `$$` signs before and after the `\begin{align*}` and `\end{align*}` blocks. It'll look like this!

||| :icon-code: Source
```
$$
\begin{align*}
\int\frac{1}{N}dN & =\int-kdt\\
\ln N & =-kt+c\\
N & =e^{-kt+c}\\
 & =e^{c}e^{-kt}
\end{align*}
$$
```
||| :icon-play: Demo
$$
\begin{align*}
\int\frac{1}{N}dN & =\int-kdt\\
\ln N & =-kt+c\\
N & =e^{-kt+c}\\
 & =e^{c}e^{-kt}
\end{align*}
$$
|||


==- Book references
Occasionally you'll see `\textitalref`. That just means the name of the book should be in italics. Simply use the section up above to figure out how to make one.


===
---

## Pushing changes to PDF

So you'll have to speak to the maker of the PDF as to updating it. This could be typos, or just general information errors. Don't forget to update the Downloads page while you're at it.
