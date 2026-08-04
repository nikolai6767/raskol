# raskol

`raskol` is a lightweight Linux command launcher and supervisor.

Its goal is to execute a command under resource constraints, monitor its
resource usage, and report how the execution terminated.

## Build

```sh
meson setup builddir
meson compile -C builddir
```
