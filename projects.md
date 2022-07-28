---
layout: page
title: Projects
permalink: /projects/
---

*This is WIP. I intend to replace this with a more comprehensive catalog-like page of my projects along with descriptions of what they do and the process of building them. For now, this is just a simple list.*

### Programming

All of my code is open-source on [Github](https://github.com/weijuwang); feel free to contribute.

#### [Intel 8080 emulator (C++)](https://github.com/weijuwang/intel8080){:target="_blank"}

See the Github repo's README.md for more details.

#### [This website](https://github.com/weijuwang/weijuwang.github.io){:target="_blank"}

This website was built with [Github Pages](https://pages.github.com/){:target="_blank"} and [Jekyll](https://jekyllrb.com/){:target="_blank"}; it is serverless and requires no HTML (though several parts of this page have custom HTML), as it converts Markdown files automatically. Thus, the source code is mostly Markdown files. If you want to make your own website like this, check out Pages' and Jekyll's websites for more information.

#### [NoComment (C)](https://esolangs.org/wiki/NoComment){:target="_blank"}

NoComment is an [esoteric programming language](https://esolangs.org/wiki/Esoteric_programming_language){:target="_blank"} I created in 2020, along with a [reference interpreter](https://github.com/weijuwang/noComment){:target="_blank"} written in plain C. It is extremely similar in syntax to many other esoteric languages like Brainf***, but it uses a stack rather than cells. In addition, no comments of any type are allowed (thus the name) -- all characters in NoComment code must be one of the 10 one-character commands. Not even newlines are allowed, so I joke that NoComment is the only language where all programs are guaranteed to be one-liners.

To this day, I have not figured out how to do multiplication in NoComment; even addition is a difficult task, as there are no built-in commands for anything more complicated than incrementing, decrementing, or simple loops. If anyone is interested, I would be happy to attempt to extend GCC or Clang to be able to compile to NoComment.

