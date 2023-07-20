---
title:  "Manage posts by tags"
date:   2023-07-20 08:42:00 +0800
category: guidance
tags: SSG jekyll
# excerpt_separator: <!--more-->
---

## how to

1. create layout page for tags
2. create include section for tag, linking to tag/sometag.md
3. then include it in layout post 
4. ensure to use `tags` in a blog which ends with `.md`
5. use python script to auto generate tag/sometag.md for each tag

## todo

- [ ] tag cloud with various font sizes
- [ ] leftside dropdown categories
- [ ] rightside toc of current article

## reference

https://longqian.me/2017/02/09/github-jekyll-tag/