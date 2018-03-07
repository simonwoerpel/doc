---
categories: doc-notes
---

```bash
./configure \
--enable-perlinterp \
--enable-rubyinterp \
--enable-cscope \
--enable-python3interp \
--with-features=huge \
--enable-multibyte \
--with-x \
--with-compiledby="Simon Woerpel <simon.woerpel@medienrevolte.de>" \
--with-python3-config-dir=/usr/lib/python3.5/config-3.5dm-x86_64-linux-gnu/\
--with-channel

make VIMRUNTIMEDIR=~/.local/share/vim/vim8

make install prefix=~/.local
```
