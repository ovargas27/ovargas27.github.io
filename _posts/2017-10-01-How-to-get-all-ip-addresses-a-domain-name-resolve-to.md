---
layout: default
title:  "How to get all IP addresses a domain name resolve to"
date:   2017-10-01 14:57:01 -0500
categories: howto networking
tags: dns ip-address
---

If you want to get all IP addresses a domain name resolves to, you can use `dig`

```
dig A api.regalii.com +short @8.8.8.8
```
