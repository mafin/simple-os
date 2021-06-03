# Simple Bootable OS #

Inspired by: https://www.youtube.com/watch?v=FkrpUaGThTQ

Build steps:
1. ```docker build buildenv/ -t simpleos-buildenv```
2. ```docker run --rm -it -v $(pwd):/root/env simpleos-buildenv```
3. ```make build-x86_64```
4. ```qemu-system-x86_64 -cdrom dist/x86_64/kernel.iso```
