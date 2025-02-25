# Parrot Security OS Installation  

---

## Why Parrot OS?  
I chose **Parrot OS** since it's designed to be used by people that are in need of security tools in their day-to-day work. Furthermore, Parrot is relatively light and is therefore suitable for my current low-end setup. This makes for a good mix of both good performance and the convenience of pre-installed tools.  

---

## Downloading Parrot OS  
I downloaded **Parrot OS version 6.3.2** from the official [download site](https://www.parrotsec.org/download/).  

I chose the **home edition** of Parrot over the security one mainly for a lighter OS that my hardware can handle, as the security version is packed with tools I won’t need that would technically “bloat” my OS and unnecessarily degrade performance. Since I won’t be using too many tools, I decided to handpick the tools and download them myself in the home edition.  

---

## Post-Installation Setup  
After installing, I was lucky enough to not run into any issues or bugs in the virtual machine during startup, allowing me to jump immediately into managing any required software updates. I made sure I was up to date by simply running the following command in Parrot’s terminal:  

```bash
sudo apt upgrade
```
Then, to ensure all updates have been implemented, I restart the system using the following command:

```bash
sudo reboot -f
```
and the OS is ready for use.

Since this virtual machine won’t be as proactively used as my host OS, I did not need to stress over customization and left the OS relatively vanilla.


