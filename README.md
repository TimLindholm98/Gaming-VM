# Gaming-VM

My gaming virtual machine xml for virsh

Commands:
```Bash
sudo vi /etc/udev/rules.d/85-input.rules

cd /etc/udev/rules.d

sudo vi /etc/libvirt/qemu.conf

sudo vi /etc/apparmor.d/abstractions/libvirt-qemu
	/dev/input/* rw,
  
sudo systemctl restart libvirtd.service

cd /dev/input/by-id
ls
 ```
