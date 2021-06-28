# Ryujinx Linux Guide
The purpose of this guide is to help your way arround using Linux and Ryujinx. The goal is to cover everything a user will need and then some. If you feel anything is missing or not explained enough feel free to open an issue or a pull request.

## Picking the distro
Linux isn't an operating system but rather a kernel (like NT is for Windows), the heart of an operating system (os) that developers use in order to create an operating system, Linux based operating systemw are called distributions or distros.
You may already have a working Linux installation but if you haven't you are probably wondering which distro suits you best out of the many that exist.
Since there are so many Linux distros, while Ryujinx strives to work everywhere it's a bit challenging to support them all so you should probably choose a more popular distribution like the ones discussed bellow.<br>
* Ubuntu: The most well known distro, based on Debian and has many flavors to choose from. It may not be the fastest or have latest packages but it's easy to setup and works out-of-the-box most of the times. If you are going to get this one opt for the Kubuntu flavor since it uses KDE (Desktop Environments are explained bellow).
* POP Os: A new contester created by hardware manufacturer System76 based on Ubuntu with some useless stuff removed (like snap packages), a new simpler theme and some features like tiling. Considering Pop Os only offers Gnome and forces you to use GPT on your hard drive it isn't recommended much.
* Mint: A well known distro based on Ubuntu (or Debian if you choose LMDE) that aims to be noob friendly. It has it's own minty green charm and is a good starting point for beginners. For performance reasons the XFCE flavor is recommended.
* Arch: Perhaps the best distro all arround. Arch lets you pick what you want your os to have and give you the tools to do it. Thanks to this we can get performance unmatched by the above distros since we can choose only the things we need and nothing more. It has a big community, the best linux Wiki and the biggest collectio of software on the Arch User Repository that has pretty much everything. One downside of Arch is that installing it isn't very easy but there's a graphical installer called Calamarch that can make up for it. If you choose Calamarch just choose KDE and nothing else when it aks you to. (If you have an Nvidia GPU you need to choose the NVIDIA drivers too, for AMD or Intel don't pick any).

## The Desktop Environment
Unlike Windows or Mac Os on Linux we have to ability to choose our desktop environment, think of it like changing the default launcher on android phone. Just like distros there are many to choose from but here are described the 3 more popular.<br>
* GNOME Shell: This is the most popular desktop environment for Linux. Many others are based on it too like Pantheon or Budgie. Sadly Gnome shell isn't very good since it's slow and doesn't give muc freedom to each users; for example you can't have desktop shortcuts. It also doesn't allow us to disable the Compositor (explained bellow) which is vital when gaming.
* KDE Plasma: By default it looks like the Windows 10 environment you are probably accustomed to but better although its highly customizable and can be turned into anything, for example some people use KDE to make Linux look exactly like Mac OS, the possibilities are endless. KDE also performs the best out of all the desktop environments. (Bonus feature:Wobbly windows!)
* XFCE: A lighter desktop environment moslty meant for older PCs, a good alternative if you don't like KDE. While it isn't particularly eye-catching by default you can make it look good.

## Installing and setting up Ryujinx
There are two ways to use Rujinx on a Linux system; you can either download it from the website and run the executable file or use the installer script Pinejinx to install it on your system like a normal app with some GPU vendor specific optimizations. Both ways will be covered.

### A. Downloading and running Ryujinx manually
First of all you have to download Ryujinx, this can be the master version from the [official website](https://ryujinx.org/download/), the LDN build from the [Patreon page](https://www.patreon.com/posts/introducing-ldn2-45268370) or a PR testing build posted by the bot on GitHub.
