FROM randomdude/gcc-cross-x86_64-elf

RUN apt update && apt upgrade -y && apt install -y grub-common nasm grub-pc-bin grub-common xorriso

VOLUME /root/env
WORKDIR /root/env
