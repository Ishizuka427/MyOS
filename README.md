![image](https://user-images.githubusercontent.com/56011102/70880319-dea05500-200b-11ea-8dbe-902d34c5349b.png)

# What is this?
It's a homebrew OS.

Displays "Hello, World".

# Execution environment
macOS
```sh
brew install nasm
brew install make
brew install qemu
```

**nasm**: This is Assembler. It replaces assembly code, which is a machine-understandable instruction program, with binary code, which is machine-understandable instructions, so that the computer can execute them.

**make**: This is a tool to automate compilation.

**qemu**: Pronounced "queue emu." The OS that you create yourself is run through this emulator. It is a so-called virtual machine.

By typing the make command as shown below, the `qemu` emulator will start and the assembly file will be compiled and executed by `nasm`.

# Run command

```sh
make qemu
```

# Work Log Articles #ja
https://hugo.suwa3.me/post/2019-12-14-os%E8%87%AA%E4%BD%9C
