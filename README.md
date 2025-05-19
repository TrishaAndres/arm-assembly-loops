# 🪖 ARM Assembly Loop Examples

This repository contains educational examples of **loop structures in ARMv7 Assembly**, with side-by-side C equivalents for clarity.

---

## 🧠 Included Loop Examples

| File           | Description                    |
|----------------|--------------------------------|
| `do_while.s`   | Simulates a `do...while` loop calculating a triangular number |
| `while_loop.s` | Classic `while (condition)` structure |
| `if_else.s`    | Conditional logic using `cmp`, `bne`, and `bal` |
| `loop.s`       | A computed expression evaluated over a loop of x = 0 to 10 |

Each file contains inline C code as a reference.

---

## 🚀 How to Run

You need an ARM-compatible toolchain or emulator such as:

- **ARM Linux virtual machine** (QEMU or Raspberry Pi)
- **Keil uVision / ARM DS-5**
- **Online tools** like [ARMv7 emulators](https://cpulator.01xz.net/?sys=arm-debian)

### Example using `gcc` on an ARM-compatible system:

```bash
as -o loop.o loop.s
gcc -o loop loop.o
./loop
```

---

## 🧰 Toolchain Requirements

as (GNU assembler)
gcc for ARM
printf syscall or ARM-compatible libc

---

## 💡 Want to See a Visual Version?

🔗 See: arm-assembly-visualizer (coming soon)
