# Kernel-4.19.255

Vanilla LTS Kernel 4.19.255 (2022-08-11) with PS4patches and Baikal patches with Vulkan Support.

How to compile this kernel?

git clone https://github.com/whitehax0r/PS4-Kernel-4.19.255-baikal.git
cd PS4-Kernel-4.19.255-baikal
mv config .config
make -j7 bzImage

Tested on latest ArchLinux.

It could work with Aeolia and Belize soutbridges consoles. Try it first and let me know.

Linux kernel
============

There are several guides for kernel developers and users. These guides can
be rendered in a number of formats, like HTML and PDF. Please read
Documentation/admin-guide/README.rst first.

In order to build the documentation, use ``make htmldocs`` or
``make pdfdocs``.  The formatted documentation can also be read online at:

    https://www.kernel.org/doc/html/latest/

There are various text files in the Documentation/ subdirectory,
several of them using the Restructured Text markup notation.

Please read the Documentation/process/changes.rst file, as it contains the
requirements for building and running the kernel, and information about
the problems which may result by upgrading your kernel.
