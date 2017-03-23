# 8086-Bootoloader-and-Kernel
A bootloader in EMU8086
How to test micro-operating system:
   1. compile micro-os_loader.asm
   2. compile micro-os_kernel.asm
   3. compile writebin.asm
   4. insert empty floppy disk to drive a:
   5. from command prompt type:
        writebin loader.bin
        writebin kernel.bin /k
