# linux-driver-hello-world
A simple "Hello, World!" driver for Linux. This module demonstrates the basic structure of a driver and how to load and unload it from the kernel. Ideal for beginners learning Linux driver development.

**modify makeFile with tab button after "all" and "clean"**

rename it **Makefile**

Ensure all files are in same directory and run the command:

**make**

Load the module:

After successfully compiling the module, load it into the kernel using the following command:

**sudo insmod hello_world.ko**

This command inserts the module into the kernel.

**Check the kernel log:**

**dmesg | tail**

To view the "**Hello, World!**" message and the "Goodbye, World!" message when unloading the module, use the following command:

**dmesg | tail**

**Unload the module:**

To unload the module from the kernel, use the following command:

**sudo rmmod hello_world**

This command removes the module from the kernel.

**dmesg | tail**
