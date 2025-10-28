# Tiny x86 Bootloader

A minimal x86 bootloader built from scratch. This project demonstrates how a CPU boots in real mode, loads the first sector from disk, and transitions into protected mode to execute custom code.

### 🧠 What It Does
- Runs in **16-bit real mode**  
- Loads and executes a small boot sector program (`boot.asm`)  
- Demonstrates the basics of writing and testing a bootable binary on x86  

### ⚙️ Tools Used
`nasm`, `bochs`, and `qemu` for assembling, emulating, and testing.

### 🚀 Run It
Assemble the bootloader:
```bash
nasm -f bin boot.asm -o bootloader.bin

