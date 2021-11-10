## Executable File and Python Package Examples

Command Line interface running an execution file or a python package 

```bash
# pulling a dockerhub image using an executable
$ ./clickLibrary pull-image ubuntu

# pulling a dockerhub image using a package
$ python -m clickLibrary pull-image ubuntu

# starting a hello world container using an executable
$ ./clickLibrary hello-world

# starting a hello world container using a package
$ python -m clickLibrary hello-world

# starting a detached hello world container using an executable
$ ./clickLibrary detached-hello

# starting a detached hello world container using a package
$ python -m clickLibrary detached-hello
```
