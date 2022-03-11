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

<Cool name={frontmatter.name} href="https://twitter.com/straight_code28" client:load />

This is so cool!

Do variables work {frontmatter.value * 2}?
