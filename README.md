nasm boot.asm -0 boot.bin

dd if=boot.bin of=helloworld.img bs=512 count=1 conv=notrunc

