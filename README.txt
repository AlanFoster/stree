= stree

home  :: FIX (url)
code  :: FIX (url)
rdoc  :: FIX (url)
bugs  :: FIX (url)
... etc ...

== DESCRIPTION:

Stree

Running within a stable environment:

```
docker run -it --rm -v $(pwd):$(pwd) -w $(pwd) ruby:2.7 /bin/bash
```

Installing libstree

```
cd libstree-0.4.3
autoconf
./configure
make
make install
```

Compiling Ruby library:

```
bundle
rake compile test
```