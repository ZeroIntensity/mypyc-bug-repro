# Repro Steps

```bash
$ git clone https://github.com/zerointensity/mypyc-bug-repro
$ pip install hatch
$ hatch build
```

On Linux, mypyc should hang with the following error:

```
error: could not create 'repro/__about__.cpython-310-x86_64-linux-gnu.so': No such file or directory
```
