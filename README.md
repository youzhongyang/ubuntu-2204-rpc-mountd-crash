# ubuntu-2204-rpc-mountd-crash
Investigate rpc.mountd core dump

Please do the following:

- Install a Ubuntu 22.04 server virtual machine on your personal computer at home. Connect the VM to the internet so it can download files.
- In your VM, clone this github repository.
- Build libtirpc3 packages. Please see the README in libtirpc folder for the needed files.
- Build nfs-kernel-server packages. Please see the FREADME in nfs-kernel-server folder for the needed files.
- Install libtirpc and nfs-kernel-server packages available in the repository as they are associated with the core dump.
- Analyze the core dump file "core.rpc.mountd.3961", figure out why it crashes, what has triggered the crash?
- Propse a fix for the issue if you could.

**Disclaimer**: The package files in this repository are not intended to be used in any production environment. 
