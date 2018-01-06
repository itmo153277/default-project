test_c 0.1
=========

Test project

Copyright &copy; 2018 Ivanov Viktor

## Installation

Install dependencies

```
# apt install autoconf-archive
```

Generate autotools scripts

```
$ sh ./autogen.sh
```

Configure

```
$ mkdir -p Debug
$ cd Debug
$ ../configure
```

Compile

 ```
$ make
```

Install as root

```
# make install
```

For more detailed information about compiling the sources see `./configure --help`.
