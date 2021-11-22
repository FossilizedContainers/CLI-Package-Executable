## Executable File and Python Package Examples

Command Line interface running an execution file or a python package 

Executable Example:

```bash
# pulling a dockerhub image using an executable
$ ./clickLibrary pull-image ubuntu

# starting a hello world container using an executable
$ ./clickLibrary hello-world

# starting a detached hello world container using an executable
$ ./clickLibrary detached-hello

# starting a detached hello world container using a package
$ python -m clickLibrary detached-hello
```

Python Package Example: ( .whl file is the download for the package itself )

~~~bash
# command to install package file
$ pip install presto-0.0.1-py3-none-any.whl

# pulling a dockerhub image using a package
$ presto pull-image ubuntu

# starting a hello world container using a package
$ presto hello-world

# starting a detached hello world container using a package
$ presto detached-hello
~~~
