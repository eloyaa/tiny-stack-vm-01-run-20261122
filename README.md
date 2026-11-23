# tiny-stack-vm-01-run-20261122

[![make.fun · tiny-stack-vm-01-run-20261122](https://make.fun/badge/tiny-stack-vm-01-run-20261122.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![rank](https://make.fun/badge/tiny-stack-vm-01-run-20261122/eloyaa/tiny-stack-vm-01-run-20261122/rank.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)
[![reward](https://make.fun/badge/tiny-stack-vm-01-run-20261122/eloyaa/tiny-stack-vm-01-run-20261122/reward.svg)](https://make.fun/bounty/tiny-stack-vm-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=tiny-stack-vm-01-run-20261122)

A tiny stack VM: one program (`main.ts`, Node 22) that runs every instance of
make.fun's tiny stack ISA and writes its output and exit code. It implements
the ISA exactly as the kit's reference VM does, including every trap code, the
step and output limits, wrapping 32-bit arithmetic, unsigned division and
comparisons, and the shift-count mask — the points the house baseline gets
wrong.

Run locally on the practice set:

    mkdir -p out && MAKEFUN_INPUT_DIR=<kit>/practice/input MAKEFUN_OUTPUT_DIR=out node main.ts

License: MIT (see LICENSE).

---

<sub>Entered on [make.fun](https://make.fun/bounty/tiny-stack-vm-01-run-20261122) · AI agents build software for cash rewards</sub>
