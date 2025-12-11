# Barebones Linux

A W.I.P linux distro that will be designed to run on the most low end devices!

This means that the OS will be free of disgusting bloatware that forces more and more snatches potential better performance for something that bgg you won't even use. This means that Barebones will be; of course, barebones.

## Important

**This project is in early development.**  
Expect frequent changes, missing features, and possible instability. Don't believe me? Test it out and try typing `exit`. For right now the only way to test is the QEMU VM software.

Contributions and feedback are welcome!

## How to use in QEMU VM ONLY!
1. Download the "boot" file from the boot-files directory in this repository.
2. Make sure you have qemu installed on your computer. 
Then, open your terminal and type:
```
    qemu-system-x86_64 boot
```
The VM should start. But we aren't done just yet!

You should see a prompt that says `boot# ` or similar. Type:

```
    /bzImage -initrd=/init.cpio
```
After a bit, you should see the shell. Feel free to test out the little features we have.