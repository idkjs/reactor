# 🚀 reactor examples 👨‍🏫

This section includes a series of small examples built in the form of _labs_
that you can read and work through to learn about reactor and how to use it.

List of labs:

1. [Spawning Processes](./01_spawning_processes/main.re)
2. [Basic Message Passing](./02_basic_message_passing/main.re)
3. [Gui KeyStroke Example](./sdl/gui_test.re)
4. [Dummy Example](./dummy.re)

## Running Examples

You can build all the examples by running:

```sh
reactor/examples λ esy dune build @all
reactor/examples λ esy dune build ./01_spawning_processes/main.exe
reactor/examples λ esy dune build @all

esy dune exec ./01_spawning_processes/main.exe
esy dune exec ./02_basic_message_passing/main.exe
esy dune exec ./sdl/gui_test.exe
esy dune exec ./dummy.exe
```

And you can run individual examples by running:

```sh
reactor/examples λ esy dune exec ./01_spawning_processes/main.exe
```

All examples include a `main.re` file.
