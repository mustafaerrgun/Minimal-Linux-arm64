# Minimal-Linux-arm64
This repository documents the step-by-step bring-up of a minimal, custom ARM64 Linux system booted on QEMU using a BusyBox-based initramfs.

The project covers the full low-level workflow, including:
- Cross-compiling a custom Linux kernel for ARM64
- Building and installing BusyBox as the user space
- Manually assembling a root filesystem (initramfs)
- Creating required device nodes
- Booting the system on QEMU’s `virt` machine
- Launching an interactive root shell without a bootloader

The goal of this project is to demonstrate a clear understanding of
embedded Linux fundamentals, kernel–userspace interaction, and early
system bring-up techniques commonly used in embedded and SoC development.
