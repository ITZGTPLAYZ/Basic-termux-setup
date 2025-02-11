
# 𝙱𝙰𝚂𝙸𝙲 𝚃𝙴𝚁𝙼𝚄𝚇 𝚂𝙴𝚃𝚄𝙿

![Made in Bangladesh] (https://img.shields.io/badge/Made%20in-Bangladesh-green?style=for-the-badge&labelColor=red)

  ![header](https://i.postimg.cc/Fs2prMSq/images-1.png)


Termux is a terminal emulator that can run a full Linux distribution on an Android device. It's a favorite tool among developers, system administrators, and tech enthusiasts who want to run Linux-based tools and scripts on-the-go conveniently. The powerful package management system allows users to quickly install and manage software on-the-fly – which is super handy if you’re coding, testing or just looking to automate everyday tasks. The setup costs are low, security in place, and no root access needed ─ Termux indeed puts Linux in your palm.


## INSTALLATION

First you need to install termux. You can download it from [**Here**](https://github.com/termux/termux-app/releases/download/v0.118.1/termux-app_v0.118.1+github-debug_arm64-v8a.apk) or from the official GitHub [**Repository**](https://github.com/termux/termux-app)
## Essential commands

![Interface](https://i.postimg.cc/4dm5v4bP/Screenshot-2025-02-11-18-30-40-64-84d3000e3f4017145260f7618db1d683.jpg)

**Just after installing the app open it and run these commands:**

To update and upgrade the packages and repos :

```
apt update && apt upgrade && pkg update && pkg upgrade -y
```
If you get this option while installing any tool or git chose "y" to continue the installation.

![permission recuest](https://i.postimg.cc/L65BP8Db/IMG-20250211-195926.jpg)


To download anything from internet in termux:

```
pkg install wget
```

To clone and use any GitHub Repository:

```
pkg install git
```

Let's install curl:

```
pkg install curl
```

Now let's give termux our file access:

```
termux-setup-storage
```

*Allow the access*

![permission recuest](https://i.postimg.cc/gjV9qKGG/IMG-20250211-195305.jpg)

![storage access preview](https://i.postimg.cc/BQpkSb67/IMG-20250211-195244.jpg)

So now let's install some basic but useful text editor Inside termux

For vim:

```
pkg install vim
```
For nano:

```
pkg install nano
```
To choose a file and edit it you can use commands like "cd" "ls" 

Lets go to our phone main directory:

```
cd storage
```
And to go back to termux use:

```
cd termux
```
You can see files or directory list using:

```
ls
```







## CHANGE THEME OF TERMUX

Yes you heard it right. You can change you're turmux theme how ever you like but now we will talk about [**This**](https://github.com/h4ck3r0/Termux-os)

First clone the git. To clone the git use:

```
git clone https://github.com/h4ck3r0/Termux-os
```
Now change the directory:

```
cd Termux-os
```
Check the list of files(optional)

```
ls
```
Now let's run the main .sh file:

```
bash os.sh
```

**You can see this interface**

![Interface](https://i.postimg.cc/sfvcCj8y/Screenshot-2025-02-11-20-26-02-19-84d3000e3f4017145260f7618db1d683.jpg)


Select all option except 4 and all select the banner text you want at the top and in the shell name enter you're name. After doing everything right not not messing up it you will get a morden and fantastic look like this

![Imodded nterface](https://i.postimg.cc/mkJjJJRQ/Screenshot-2025-02-11-20-38-15-06-84d3000e3f4017145260f7618db1d683.jpg)

**The theme credit goes to Raj [Aryan](https://github.com/h4ck3r0) or [h4ck3r0](https://github.com/h4ck3r0)** please go and check his profile and YouTube channel he did a very good work 👍

Thanks for giving you're time I hope you have a great day 😘 👍

