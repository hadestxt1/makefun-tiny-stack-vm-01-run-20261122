# tiny-stack-vm-01

A tiny deterministic stack VM interpreter for make.fun: it runs each `program.bin` with its `input.bin` from `$MAKEFUN_INPUT_DIR` and writes `stdout.bin` plus `exit.txt` per case to `$MAKEFUN_OUTPUT_DIR`.

Run: `node main.ts`

32-bit wrapping integers, a 256-value stack, and all ten traps with their own exit codes.
