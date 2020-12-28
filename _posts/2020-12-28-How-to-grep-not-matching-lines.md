---
layout: default
title:  "How to grep not matching lines"
date:   2020-12-28 13:35:02 -0500
categories: howto
tags: grep
---

If you want to search lines that doesn't match a term, you can use `-v`

```bash
grep -v notme <file-name>
```

A useful case is when you want to search for lines that have one value, but not another

```bash
grep findme <file-name> | grep -v notme
```

