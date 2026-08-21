# c0rewing
An independent, lightweight x86_64 Linux system built from scratch (LFS-based).

Download Link
* You can download the rootfs archive here: https://drive.google.com/file/d/1DncYnsn5Cqh9tUbGIXbfGRQxer-jBmMY/view?usp=drive_link

System Core & Utilities
* Base System: Essential GNU/Linux base utils.
* Network: Working internet connection out of the box.
* Terminal Multiplexer: tmux pre-installed for advanced CLI layouts.
* System Monitor: htop for process and resource tracking.
* System Info: fastfetch to display system specs.

Graphical Environment
* Window Manager: Fluxbox (ultra-lightweight, fast window manager).
* Display Server: Full Xorg server implementation with xinit.
* Graphics: Native support for Intel HD Graphics (Kernel can be recompiled for other hardware).
* Toolkit: GTK compilation framework included.

Terminal Fun & Easter Eggs
* cmatrix - Classic digital rain screen effect.
* aafire - ASCII art burning fire animation.

Important Notes & Customization
* Fastfetch Logo: Please do not delete /root/ascii.txt if you want to keep or customize the custom ASCII logo used by fastfetch!
* Developer Note: This is my very first release, so it still contains some of my personal build files. I sincerely apologize for the clutter! In the next release, I will completely clean up the environment and remove all leftover files.

Installation & Defaults
* Deployment: Copy the rootfs directly to your target drive and install the GRUB bootloader.
* Default Credentials: 
  * Username: root
  * Password: root (Please change this immediately after your first boot for security!)
