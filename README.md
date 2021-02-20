# Ryujinx Linux Guide
If you are an AMD/Intel GPU user (or even an NVIDIA one) you may want to switch to Linux for various reasons, freedom, no surveilance, performance. This guide aims to help you.

## Picking a distro
If you don't already have a Linux distro installed you may need some guidance as to which distro you shall choose. In general Arch is a recommended distro due to the vast ammount of latest software available to it thanks to Pacman (the package manager) and the AUR (the all-inclusive arch repository where anyone can submit packages) and the Arch Wiki which helps in every occasion. While Arch is so good, it requires some skill and time to install it for the first time since when you boot the Live-CD you are met with a TTY (terminal) interface where you should use commands to install the OS although this isn't as bad as it sounds and is the recommended way. If you want a Live CD with an installer and a GUI for installing Arch, I recommend Reborn OS, an Antegros fork.

## Picking the DE
Another huge advantage of Linux is the ability to choose your desktop environment. There is a vast collection of Desktop Environments and Window Managers to choose from depending on your workflow. You want to avoid using GNOME or any based DE (MATE, Cinnamon, Budgie, Unity) since GNOME doesn't allow any customization, doesn't allow desktop shortcuts and the performance isn't great due to the innability to turn off the compositor and because it's a resource hog. For the general user I recommend KDE (not on Wayland) since it's performant, compositor can be disabled with a simple keybind (Alt+Shift+F12 by default) and is customizable. If you are a laptop user and are very limited on the GPU side (eg. Mobile Maxwell cards) you may choose XFCE (and disable the compositor from settings) or LXQt depending on which you find the most attractive.

## Installing the drivers
One more big advantage of the Linux kernel is that the drivers are included. There are cases although that you may still need to install one for the GPU.

### NVIDIA users
Although, since Maxwell NVIDIA locked their cards so you want to use their propriatary driver instead of the preincluded one (Nouveau).
In order to get the latest drivers
