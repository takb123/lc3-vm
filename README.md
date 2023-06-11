# lc3-vm
This is a Virtual Machine written in C simulating the [LC3](https://en.wikipedia.org/wiki/Little_Computer_3). [^1]
## Usage
1. Compile `src/lc3.c`

Using clang:
```console
clang -o lc3 src/lc3.c
```
Using gcc:
```console
gcc -o lc3 src/lc3.c
```

2. Run the VM while passing in the `.obj` games[^2]

```console
./lc3 games/2048.obj
```

```console
./lc3 games/rogue.obj
```


[^1]: Made by following [this tutorial](https://www.jmeiners.com/lc3-vm/index.html). Special thanks to Justin Meiners and Ryan Pendleton.
[^2]: Downloaded from the above tutorial. Again, special thanks to Justin Meiners and Ryan Pendleton.
