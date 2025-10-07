# My first C program

Literally my first C program. (Well, apart from my Black Box submission.)

## Usage

### Inspect memory using the command-line

Compile with debug symbols enabled:

```bash
gcc -d -o data_explorer data_explorer.c
```

Start GDB:

```bash
gdb ./data_explorer
```

### Inspect memory using VSCode

1. Add a breakpoint to `data_explorer.c`
2. Hit <kbd>F5</kbd>