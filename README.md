buildroot-prebuilt
============================
### Overlay
- [hugh712/mp3_player](https://github.com/hugh712/mp3_player)

### Tutorials
- [Buildroot and compiler on target | LupLab @ UC Davis](https://luplab.cs.ucdavis.edu/2022/01/06/buildroot-and-compiler-on-target.html)
- [Introduction · Buildroot架構解析](https://hugh712.gitbooks.io/buildroot/content/)

### x86_64
- [buildroot编译运行QEMU X86_64](https://jgsun.github.io/2020/05/28/qemu-x86-64/)
  - ```bash
    sudo qemu-system-x86_64 -M pc -kernel output/images/bzImage \
      -drive file=output/images/rootfs.ext2,if=virtio,format=raw \
      -append "rootwait root=/dev/vda console=tty1 \
      console=ttyS0" \
      -net nic,model=virtio \
      -net user -nographic \
      -enable-kvm
    ```
### aarch64


### arm
- [mxOBS/imagebuilder](https://github.com/mxOBS/imagebuilder)
