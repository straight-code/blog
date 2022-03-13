---
setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Blog 1
publishDate: 28/02/22
name: straight-code
value: 128
description: about blog 1
---

# About Me 
I'm straight-code 
<img src="https://straight-code.github.io/assets/straight-code.png" style="width:300px; margin-left: 30%;" >
<Cool name={frontmatter.name} href="https://twitter.com/straight_code28" client:load />
This is so cool!

