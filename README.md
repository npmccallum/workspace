The strategy this repo takes is to wrap the linker to perform operations on the linker arguments.

To run a build, for example, do the following in the root directory:

```
$ RUSTFLAGS="-C linker=`pwd`/cc" cargo build
```
