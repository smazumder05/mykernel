# mykernel

My attempt to write a kernel completely in assembly. It does not do much, apart from running a command prompt and spitting out a message but goes through all the steps of any other kernel.
This project is just a assembly language refresher for me.

Use the following commands to compile and run in [Qemu](http://wiki.qemu.org/Main_Page)

```bash
$ nasm boot.asm -o bootable.bin
$ qemu-system-x86_64 bootable.bin
```

#### Next steps
1. Provide a minimal shell

#### References

1.  [Intel 64-bit Software Developer's Manual](http://www.intel.com/content/dam/www/public/us/en/documents/manuals/64-ia-32-architectures-software-developer-manual-325462.pdf)

