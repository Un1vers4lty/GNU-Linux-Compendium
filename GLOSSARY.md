# Glossary of Terms
• Core Concepts & Architecture 
      1. Unix: A powerful, multi-user operating system originally developed in the 1960s at Bell Labs, which served as the foundation for modern macOS and Unix-like operating systems.
      2. POSIX: (Portable Operating System Interface) A family of standards defined by the IEEE to maintain compatibility between different operating systems (mainly Unix variants).
      3. GNU: (GNU's Not Unix) A massive project founded by Richard Stallman to create a completely free, Unix-like software operating system.
      4. Linux: Strictly speaking, just the open-source kernel created by Linus Torvalds in 1991; commonly used to refer to entire operating systems (GNU/Linux) built around it.
      5. Linux Distribution (Distro): A complete operating system packaged by taking the Linux kernel, system utilities, a package manager, and software applications (e.g., Ubuntu, Fedora, Arch).
      6. Kernel: The core foundational layer of an operating system that acts as a bridge between applications and the actual physical hardware (CPU, memory, devices).
      7. Open-Source: Software whose source code is made freely available to the public, allowing anyone to view, modify, and distribute it.
      8. Rolling-Release: A software update model where the operating system continuously receives small updates rather than major, periodic version upgrades (e.g., Arch Linux).
      9. Immutable/Atomic: A system design where the core operating system files are read-only to prevent corruption and system-breaking errors, updating as a single, atomic unit.
      
 • Desktop & Interface 
      1. Desktop Environment (DE): A complete graphical user interface suite including panels, window managers, icons, file managers, and settings apps (e.g., GNOME, KDE Plasma).
      2. Window Manager: Software that controls the placement, appearance, and behavior of windows on the screen within a windowing system.
      3. Graphical User Interface (GUI): A visual interface allowing users to interact with electronic devices through graphical icons and visual indicators.
      4. Command Line Interface (CLI): A text-based interface used to interact with software and operating systems by typing explicit commands.
      5. Compositor: A window system component that takes the graphical output of independent windows, applies effects (like transparency or shadows), and composites them onto the screen.
      
 • Software & Package Management
      1. Repository (Repo): A centralized server or storage location from which software packages can be retrieved, installed, and updated.
      2. Package Manager: A tool that automates the process of installing, updating, configuring, and removing software packages and their dependencies.
      3. Flatpak / Snap: Universal, sandboxed package formats designed to run securely across any Linux distribution regardless of its base package manager.
      4. Source Code: The human-readable set of instructions and programming statements written by a developer before it is compiled into a program.
      5. Compile: The process of translating human-readable source code into machine-readable binary code that a computer's CPU can execute.
      6. Driver: Specialized software that allows the operating system to communicate with hardware components (like graphics cards or printers).
      
 • Performance & Compatibility Layers 
      1. Swap Space: A designated area on a storage drive (or a file) used by the operating system as virtual memory when physical RAM runs low.
      2. Wine: (Wine Is Not an Emulator) A compatibility layer that allows Windows applications to run directly on POSIX-compliant operating systems like Linux and macOS.
      3. Proton: A specialized compatibility tool developed by Valve (based on Wine) designed to seamlessly run Windows games through Steam on Linux.
      4. DXVK: A translation layer that converts DirectX 10/11/12 graphics calls into Vulkan, enabling high-performance gaming on non-Windows platforms.
      5. Compatibility Layer: Software that translates system calls or instructions from one platform or architecture into ones understandable by another.
      6. Translation layer: A specific subset of compatibility software that directly converts instructions from one API or architecture to another in real-time.
      
 • Filesystems 
      1. APFS: (Apple File System) The proprietary, modern default filesystem used by Apple for macOS, iOS, and other Apple devices.
      2. HFS+: (Hierarchical File System Plus) Apple's older legacy filesystem used before APFS.
      3. ext4: (Fourth Extended Filesystem) The traditional, stable, and widely-used default journaling filesystem for the Linux ecosystem.
      4. XFS: A high-performance 64-bit journaling filesystem optimized for handling large files and high-throughput storage scaling.
      5. Btrfs: A modern copy-on-write (CoW) filesystem for Linux that supports advanced features like built-in snapshots, pooling, and checksums.
      6. exFAT: (Extended File Allocation Table) A Microsoft-created filesystem optimized for flash drives, allowing cross-platform compatibility between Windows, macOS, and Linux.
      7. NTFS: (New Technology File System) The proprietary journaling filesystem standard used by Microsoft Windows.
      8. FAT32: An older, universally compatible filesystem with a strict file size limit of 4GB, used widely on small USBs and embedded devices.
      
• Low-Level System Virtual Files
      1. Proc (/proc): A virtual filesystem in Linux that contains runtime system information and kernel parameters as text files.
      2. Sysfs (/sys): A virtual filesystem that exports information about devices and drivers from the kernel into user space.
      3. Tempfs: A filesystem that temporarily stores all its files in volatile memory (RAM) rather than persistent storage for ultra-fast access.
      
 • Community & Culture
      1. Upstream / Downstream: "Upstream" refers to the original creators or maintainers of software; "downstream" refers to distributions or developers who take that software, modify it, and package it for end-users.
      2. Rice / Ricing: The act of heavily customizing and aesthetically optimizing a Linux desktop environment or window manager shell.
      3. Dependency: An external library, package, or piece of software that another program requires in order to run correctly.
      4. Broken Dependency: A frustrating state where a required package is missing, outdated, or conflicts with the system, preventing software installation or execution.
      5. RTFM: (Read The Fucking Manual) A classic piece of community advice directed at users asking questions whose answers are easily found in the official documentation.
      6. Dotfiles: Configuration files (usually starting with a dot, e.g., .bashrc) used to customize user settings, applications, and shells.
      7. Bootloader: Low-level software (like GRUB) that loads the operating system kernel into memory when the computer first turns on.
      8. Init: The very first process (PID 1) started by the Linux kernel during boot, responsible for initializing the rest of the user space (e.g., systemd).  
      9. User space: The memory and execution area where user applications, utilities, and desktop environments run, completely separated from the privileged kernel space.
      10. Distro-Hopping: The common hobby among Linux users of constantly switching from one Linux distribution to another to find the best fit.
