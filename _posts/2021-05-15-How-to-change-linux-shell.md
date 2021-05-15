---
layout: default
title:  "How to change linux shell"
date:   2021-05-15 11:21:02 -0500
categories: howto
---

You can see what shell you are using with

```bash
echo $SHELL
```

To see the availble shells

```bash
cat /etc/shells
```

Change the assigned shell

```bash
chsh
```

And write down the path, show in `/etc/shells`, that you want to use.

To reload your session with the new shell, simply run

```bash
su - yourid
```

