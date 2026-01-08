# OS Development Project

A custom x86 operating system developed from scratch in Assembly language. This educational project is to dive into  low-level system programming concepts .
For now the OS loads the GDT and  then jumps to the kernel.THe CPU is completely stable in 32 bit protected mode.The bootlodaer gurantees this.
The kernel then write some data to VGA for debugging purposes and then loop stably.
## Project Structure

- `boot.asm` - Bootloader code (first stage)
- `stage2.asm` - Second stage bootloader
- `utils.asm` - Utility functions and macro
## Building the OS

To build the OS, you'll need:
- NASM (Netwide Assembler)
- QEMU (for emulation)

### Build Commands

```bash
./build
```

## Running in QEMU

```bash
./run
```

## Debugging

To debug with QEMU and GDB:

```bash
./debug
```
