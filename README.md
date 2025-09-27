# assignment1
LINUX PROGRAMMING ASSIGNMENT-1

1. What is Linux OS? State three pros and cons
Linux is an operating system built on the Unix model. It is open-source, meaning the source code is freely available for anyone to use, modify, and redistribute. It manages system hardware, software applications, and user processes.
Advantages
●	Cost-effective – completely free to use, with no licensing fees.

●	Highly reliable – known for stability and minimal crashes.

●	Flexible – runs on diverse platforms, from laptops to supercomputers and servers.

Limitations
●	Some commercial applications are not available for Linux.
●	Beginners may find it difficult due to heavy reliance on command-line usage.

●	Certain hardware devices may not have strong driver support.

2. Linux vs. macOS vs. Android vs. Windows


Criteria	Linux	macOS	Android	Windows
Licensing	Free and open(GPL)	Proprietary (Apple-owned)	Open-source base, Google-managed	Proprietary (Microsoft-owned)
Interface	Multiple desktops (GNOME, KDE, etc.)	Polished Apple UI	Touchscreen-optimized	Desktop based
Hardware Use	Servers, PCs, embedded systems	Only Apple devices	Smartphones, TVs, tablets	Wide range of desktops & laptops
Security	Strong permissions, open patches	Secure but closed	Varies by manufacturer	Frequent malware attacks
Software Management	Package managers (APT, YUM, Pacman)	App Store	Google Play Store	EXE/MSI, Microsoft Store
Major Usage	Servers, research, development	Creative industries	Mobile OS dominance	Business, home, gaming


3. Why is Linux preferred for Mainframe Servers?
●	Handles massive workloads – scales efficiently for thousands of concurrent processes.

●	Supports legacy systems – maintains backward compatibility through POSIX standards.

●	Dependability – capable of running continuously for years without a reboot.

4. Linux File System Structure
Linux uses a tree-like hierarchy beginning at the root /.
Key Directories
●	/bin – essential user commands

●	/sbin – system-level commands

●	/etc – configuration files

●	/home – personal user directories

●	/var – variable data (logs, cache)

●	/usr – applications & libraries

●	/tmp – temporary storage

5. How Red Hat earns revenue despite Linux being free
Red Hat earns revenue not from selling Linux, but from services:
●	Enterprise subscriptions (Red Hat Enterprise Linux licensing)

●	Technical support & training for businesses

●	Consulting services for enterprise solutions

●	Cloud & container platforms (e.g., OpenShift)

6. Command to display date and time
date

7. Command to check system uptime
uptime

8. Difference between shutdown -h now and halt
●	shutdown -h now → Gracefully ends processes, unmounts drives, and powers off.

●	halt → Immediately stops CPU operations without ensuring a clean shutdown.
9. Compare init 0 and shutdown -h. Which is safer?
●	init 0 → Directly changes the runlevel to shutdown, minimal warnings.

●	shutdown -h → Notifies users, safely ends processes, unmounts file systems.
 Note: shutdown -h (prevents corruption and data loss
10. Risks of powering off a server without shutdown
●	Incomplete disk writes → filesystem corruption.

●	Applications lose unsaved data.

●	Databases face integrity issues.

●	Hardware stress on storage devices.

Brainstorming Section

a)	Can we build our own OS using the Linux kernel?
 
Yes. The Linux kernel is open-source, so new distributions can be built by customizing kernel, tools, and UI.


b)	Challenges:
●	Requires deep knowledge of kernels, drivers, and system internals.

●	Complex package management & updates.

●	Hard to build a strong user & developer community.

c)	Indian engineers contributing in this area:
●	Kushal Das – Fedora developer, Python contributor.

●	Shakthi Kannan – Linux kernel & free software evangelist.

●	Balbir Singh – Linux memory management (IBM/Red Hat).

●	Harish Pillay – Linux Foundation & open-source advocate.

Submitted by:
JESTIN JERALD A 
ENG24CY0116
2nd year- 3C
Cybersecurity

