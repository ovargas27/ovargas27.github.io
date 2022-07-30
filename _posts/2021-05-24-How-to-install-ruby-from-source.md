---
layout: default
title:  "How to install linux from source code"
date:   2021-05-24 17:21:02 -0500
categories: howto
---

For Ruby v3.0.1 will be something like

```bash
curl --remote-name https://cache.ruby-lang.org/pub/ruby/3.0/ruby-3.0.1.tar.bz2
tar -xjvf ruby-3.0.1.tar.bz2
cd ruby-3.0.1
./configure --prefix="$HOME/.rubies/ruby-3.0.1" --with-opt-dir="$(brew --prefix openssl):$(brew --prefix readline):$(brew --prefix libyaml):$(brew --prefix gdbm):$(brew --prefix libffi)"
make -j2
make install
```

I use this with chruby, please, let me know if it works with your Ruby manager
