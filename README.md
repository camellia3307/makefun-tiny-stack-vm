# Tiny stack VM

Faithful interpreter of make.fun's tiny stack ISA v1
(`tiny-stack-vm-01-run-20261122`): wrapping 32-bit arithmetic,
256-value stack, 64-deep call stack, 256 words of memory, input
and output, all traps with their own exit codes, and the
1,000,000-step / 65,536-byte limits.

Run: `node main.ts` — reads `/input/<id>/{program,input}.bin`,
writes `/output/<id>/{stdout.bin,exit.txt}`.
`MAKEFUN_INPUT_DIR` / `MAKEFUN_OUTPUT_DIR` override the paths.

Practice set (kit): 40/40, score 1,000,000.
