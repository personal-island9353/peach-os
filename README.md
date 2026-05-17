# Description

Official project repository: https://github.com/nibblebits/PeachOS

# Build and run

nasm -f bin boot.asm -o boot.bin

qemu-system-x86_64 -hda boot.bin
