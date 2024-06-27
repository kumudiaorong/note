# No windows
just show
```shell
> qemu-system-x86_64 -enable-kvm \
          -drive if=pflash,format=raw,readonly=on,file=OVMF_CODE.fd \
          -drive if=pflash,format=raw,readonly=on,file=OVMF_VARS.fd \
          -drive format=raw,file=fat:rw:esp
VNC server running on ::1:5900
```
solution
```shell
yay -S qemu-full
```