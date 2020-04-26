# stree

Simple Ruby wrapper for the C libstree library.

## Running

Running within a stable environment:

```
docker run -it --rm -v $(pwd):$(pwd) -w $(pwd) ruby:2.7 /bin/bash
```

Installing libstree

```
tar xzf libstree-0.4.3-pre2.tar.gz
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

## Resources

- Tenderlove's Writing Ruby C Extensions:
    - [Part 1](https://tenderlovemaking.com/2009/12/18/writing-ruby-c-extensions-part-1.html)
    - [Part 2](https://tenderlovemaking.com/2010/12/11/writing-ruby-c-extensions-part-2.html)
- [Creating extension libraries for Ruby](https://github.com/ruby/ruby/blob/ea32715e004dc8f56dc599883d3183d7b2635f81/doc/extension.rdoc)
