---
tags:
  - Linux
  - Basic
  - HowTo
  - Tutorial
author: Dominik Boczkowski
date: 2025-07-15
title: Start with Linux
description: In times when Microsoft is making the moves it's making, and macOS is changing its UI to Liquid Glass, which doesn't appeal to everyone, more and more people are considering alternatives.
robots: true
charset: UTF-8
---
In times when Microsoft is making the moves it's making, and macOS is changing its UI to Liquid Glass, which doesn't appeal to everyone, more and more people are considering alternatives. Not everyone knows that there are many other options besides these two giants, for example Linux. Linux (purists would probably say we're talking about the GNU/Linux system 🤓) is an open-source and free-to-use, UNIX-based operating system created by Linus Torvalds[^1]. Its kernel was written during the creator's studies and is still being developed today. But enough about its history.

![Linux logo](https://upload.wikimedia.org/wikipedia/commons/a/ab/Linux_Logo_in_Linux_Libertine_Font.svg)

# Why Linux?

The little penguin is like a blank slate, allowing the user to shape a system tailored to them like a tuxedo. Depending on the Linux distribution, you get different elements of the system besides its kernel and build upon it with packages that create your operating system. You can choose the look and feel of your system, which applications are installed, what tools you need, and even which package manager you want to use. This provides unlimited possibilities to adapt the system to your needs. Due to its architecture, it can even run in a live environment, so you don't have to install it to use it (for example, for testing or even for data security).

# How to Choose a Linux Distro?

The previously mentioned distributions are collections of system features. Depending on the distribution's philosophy, you can have a stable system, a rolling release (the latest software), or Long Term Support. In the past, the choice of distribution was very important. Different features, environments, and tools were provided in a package, and with low bandwidth or, in some situations, no internet, choosing a distribution meant you were stuck with a particular set. Today, thanks to the huge (and still growing) community, the availability of packages, and the open-source nature of Linux, we can do what we want on any distribution we want. Linux distributions are divided into main branches, i.e., Slackware[^2], Debian[^3], Red Hat[^4], Arch[^5], NixOS[^6]. The rest of the distributions are their derivatives. Depending on what we expect from our Linux, it is worth choosing a base to build our system on.

# Which Linux to Choose?

When choosing a distribution, we must decide how we want to use it and which features are important to us. Below you will find a list of the main distributions and their philosophies.

- **Debian:**
    - Stable and reliable
    - The foundation for a large number of other distributions (Linux Mint, Raspbian, Ubuntu)
    - Repositories contain only open-source packages
    - A wide selection of software packages
    - Support for multiple hardware architectures (x86, ARM, etc.)
    - Often chosen for servers and production systems
- **Slackware**
    - Stable and minimal (installs only the minimum number of packages)
    - Manual and text-based system configuration via configuration files
    - Text-based installer
    - Manual package installation
    - Unix-like data structure and principles reminiscent of FreeBSD or macOS
    - Long development history - the oldest existing distribution
- **Red Hat**
    - Aimed at businesses and corporate applications
    - Known for its business support and stability
- **Arch Linux**
    - Rolling release model providing the latest software versions on their release day
    - Minimal and easy to configure
    - Uses the Arch repository as well as user driven repository (AUR)
- **NixOS**
    - Defined by a single configuration file
    - The atomic structure allows for easy system recovery, reproduction, and repair
    - Packages and their dependencies are isolated from each other, which provides greater stability

Knowing the most important distributions and their philosophies, we can choose what we need. Acknowledging that this can be overwhelming, I can personally recommend Linux Mint for beginners. It's a system with great user support and a set of packages that turn Debian into a Plug and Play system. However, if you want something based on Red Hat, I recommend Fedora. It is a distribution that combines the stability of business support with a large number of packages, along with easy installation and configuration. If you want something that has the latest packages (including drivers for GPU or CPU), the best choice would be CachyOS. Based on Arch Linux, this distribution allows for an easy system installation using a graphical installer. Arch Linux is also popular among people who enjoy gaming due to the quick availability of the latest drivers. Used by Valve (SteamOS), Arch Linux is a good option for avid gamers. And the last distribution on the list from the SUSE family is openSUSE, which is user-friendly for various applications. If you still don't know what's best for you, I recommend taking [this quiz](https://distrochooser.de).

# I've Chosen a Linux Distribution, What's Next?

When choosing a distribution, it's not just about the system's philosophy. If we want to use this system for more than just a server, we need a way to interact with it. A Window Manager (WM for short) will help us with that. Linux allows you to change the WM on any distribution. This gives you the ability to tailor the tuxedo to your needs. First, let's ask ourselves what our operating system should be like. Linux allows for more than just the windows known from Windows or macOS. The window manager manages the windows, and the type of window manager we want depends on how we want to use the system. We can divide them into:

| Window Manager | Description                                                              | Examples                                      |
| -------------- | ------------------------------------------------------------------------ | --------------------------------------------- |
| Stacking       | Allows to freely move and change windows (like in Microsoft OS or macOS) | KWin, Mutter, Openbox, itd                    |
| Tiling         | Windows are automatically place next to each other without colliding     | i3, BSPWM, awesomeWM, xmonad, Sway, Hyperland |
| Dynamic        | Is a mix of Stacking and Tiling                                          | dwm, herbstluftwm                             |


After choosing the type of Window Manager, we can choose a Desktop Environment (DE for short). A DE is a package that contains the entire GUI (Graphical User Interface) of our system. It also includes a window manager. Unfortunately, if we want types of WMs other than stacking, we will have to create our own DE from building blocks. However, if you don't want to do that, there are ready-made DE sets to choose from:

- **KDE Plasma** - A Windows-like DE with huge customization possibilities
- **GNOME** - A DE closer to macOS, and customizable thanks to extensions
- **Cinnamon** - A DE created for Linux Mint, which is somewhere between Windows and macOS
- **Deepin** - A DE that places a strong emphasis on appearance
- **LXQt** - A lightweight DE, created to run on very weak hardware
- **Xfce** - Another lightweight DE

![Example of DE customization](https://i.redd.it/c0ilzexndo881.png)

# Are you ready?

As it turns out, Linux is more than an alternative to Windows or macOS. It is an open platform to build your ideal operating system. Regardless of whether it's supposed to be a system ready to work right away or a minimalist system polished to the smallest pixel and optimized to squeeze every last drop of performance from your hardware. Knowing the main distributions, what Desktop Environments are, and understanding how a Window Manager works, you can finally make an informed choice of the system that best suits your needs. Regardless of whether you want a simple and convenient system or a powerhouse for gaming.

Consider this:

- What kind of system do you want? Stable and proven? Or maybe always the latest and continuously developed?
- Do you prefer a ready-made graphical environment that works smoothly "out of the box"? Or maybe you want to configure your system yourself to make it truly yours?
- Do you want to learn new tools? Or do you value simplicity and ease of use more?

Regardless of your choice, I encourage you to try Linux! Perhaps the little penguin will peck you, and you'll catch the fever called Linux!

![Matrix Morpheus](https://w.wallhaven.cc/full/l3/wallhaven-l336gp.png)

---
[^1]: https://pl.wikipedia.org/wiki/Linus_Torvalds
[^2]: http://www.slackware.com/
[^3]: https://www.debian.org/index.pl.html
[^4]: https://www.redhat.com/en
[^5]: https://archlinux.org/
[^6]: https://nixos.org/
