---
layout: default
title:  "How to split long lines"
date:   2022-07-29 19:52:02 -0500
categories: howto
---

Use fold to split long lines of text

```bash
fold -s -w80 <filename>
```

**-s** so it respect long works, and fold lines only on after a blank character

**-w** to specific the width, default is 80
