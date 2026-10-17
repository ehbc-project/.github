# EHBC

Extensible Homebrew Computer, a homebrew computer built around the Motorola 68030. The board design went through several revisions. The machine that actually ran is the emulated `proto1` in a MAME fork, with its own boot firmware and an operating system, EMOS, which later became [foliOS](https://github.com/foliOS-project).

The project is on hold.

| Repository | Contents |
| --- | --- |
| [ehbc-firmware](https://github.com/ehbc-project/ehbc-firmware) | Boot firmware: device setup, configuration utility, bootloader search |
| [emos](https://github.com/ehbc-project/emos) | EHBC Modular OS |
| [mame](https://github.com/ehbc-project/mame) | MAME fork with the `proto1` driver |
| [ehbc-proto1-board](https://github.com/ehbc-project/ehbc-proto1-board) | KiCad board designs |
| [homebrew-toolchain](https://github.com/ehbc-project/homebrew-toolchain) | Homebrew formulae for the `m68k-unknown-elf` toolchain |
