# FreeRTOS on RISC-V (QEMU)

This repository demonstrates running **FreeRTOS** on a **RISC-V RV32** virtual platform using **QEMU**.

## Target
- Architecture: RISC-V RV32
- Emulator: QEMU `virt` machine
- RTOS: FreeRTOS
- Demo: RISC-V_RV32_QEMU_VIRT_GCC

## Build Instructions
```bash
cd Demo/RISC-V_RV32_QEMU_VIRT_GCC/build/gcc
make
```

## Cloning Instructions
Note: This repository uses git submodules. Clone with:
```bash
git clone --recurse-submodules https://github.com/saleha-zip/FreeRTOS_RISCV_QEMU_Project
```

