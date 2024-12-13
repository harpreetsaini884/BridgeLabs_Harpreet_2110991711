# Friday

Today i have done the Topics 

Os Architecture 

Monolithic Structure

What it is: A single, large kernel with all OS functions 
Pros: Fast and efficient, components talk directly.
Cons: Hard to debug or update due to its complexity.
Examples: UNIX, MS-DOS.
Layered Structure

What it is: Organized in layers (e.g., hardware at the bottom, user interface at the top). Each layer talks only to its neighbors.
Pros: Easier to maintain and debug; modular design.
Cons: Slower due to communication between layers; designing layers can be tricky.
Examples: THE OS.
Microkernel Structure

What it is: A minimal kernel for essentials (e.g., memory, communication), with most services running in user space.
Pros: Highly reliable and modular, easy to expand.
Cons: Slower due to extra communication between kernel and user space.
Examples: macOS, QNX, Minix.
Modular Structure

What it is: A small kernel with loadable modules for extra features, blending monolithic and microkernel ideas.
Pros: Flexible, easy to update parts without restarting.
Cons: Managing module dependencies can be complex.
Examples: Linux.
Client-Server Structure

What it is: Services are split into isolated servers, and the kernel mediates communication between apps (clients) and services.
Pros: Faults in one service don’t crash the whole system; reliable.
Cons: Slower due to communication overhead.
Examples: Windows NT.
Virtual Machine Structure

What it is: A hypervisor provides virtual hardware for running multiple OS instances.
Pros: High security and flexibility, supports multiple OSes on one machine.
Cons: Heavy on resources, adds overhead.
Examples: VMware, VirtualBox, Xen.

2) Functions of Os

/ - The root of the filesystem; everything starts here.
/bin - Essential commands and binaries for all users (e.g., ls, cp).
/boot - Boot loader files like the kernel and GRUB.
/dev - Device files for hardware like USB and terminals.
/etc - System-wide configuration files and scripts.
/home - Personal directories for user files and settings.
/lib - Libraries required by programs in /bin and /sbin.
/media - Mount points for removable media like CDs and USBs.
/mnt - Temporary mount point for filesystems.
/opt - Optional add-on application software.
/sbin - System binaries for administrative tasks (e.g., reboot, fdisk).
/srv - Data for services like web and FTP servers.
/tmp - Temporary files, cleared on reboot.
/usr - Secondary hierarchy for user programs, libraries, and documentation.
/proc - Virtual filesystem with info about processes and system.



3)Features of Linux 

 Resource Management
 Memory Management
 Process Management 
 Security
 File Management
 Networking 
 Backup Recovery

4) Linux Kernel
