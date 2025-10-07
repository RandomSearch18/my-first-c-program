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

Then use the debugger:
```
(gdb) break 7
(gdb) run
(gdb) print a_char
$1 = 65 'A'
(gdb) print an_unsigned
$2 = 210 '\322'
(gdb) print a_short
$3 = 12345
(gdb) quit
```

### Inspect memory using VSCode

1. Add a breakpoint to `data_explorer.c`
2. Hit <kbd>F5</kbd>