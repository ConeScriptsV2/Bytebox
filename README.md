# Bytebox [V1]
This project is an open source project to act as your mini-server for when you are in heavily restricted areas.

Developer Wise, this project is a linux distro. Pushing whatever tech its running on to the max of its capabilities with a user interface. Complete with SSH on terminal and in browser.

Note: This project is for educational and entertainment purposes. **Do not attempt to host bytebox on a public network. Host it on a hotspot instead, because hosting an unwanted server on a public network is illegal and will most likely not work due to the configuration.**

# Bytebox Recipe
As you know, Bytebox isnt really free. It requires some certain hardware to run on.
**You are going to need:**

Hotspot/Wifi SSID and Password

Device that can run a .img file or a storage device


But since its called Bytebox, heres my personal recipe for when im on the go:

Hotspot (SSID and Password)

Orange Pi (Can be a Raspberry Pi)

Orange Pi Casing (To protect the Orange Pi)

Battery + Short USB to USB-C Cable (Keep the Orange Pi turned on wirelessly)


This overall helps you run Bytebox the intended way. *This distro will not provide you a UI Interface or a desktop directly. It only hosts a HTML Page at bytebox.local*

Alternatively, if you're looking to host this onto a public domain that is completely fine with me. Even though the usage was designed for local hosting.

# What does this do?

It hosts a local server on your network, the URL name is **bytebox.local** and it hosts 24/7. If the server is not working, **Your connection might be restricting bytebox from hosting freely on the network.**

# QNA

**Does this work on any computer?**

Yes. Aslong as you can replace the OS and access the internet.


**Is it free to use?** 

Yes, aslong as you or someone else hosts it.


**How do i debug the box?**

Connect a monitor into the hardware, it displays a live console of whats happening.


**How do i change SSID Settings?**

Theres a file named "startup.env" and it contains all the network settings you need. (Rebuild required) *This future will be replaced soon.*

**What is this kernel?**

Its running off Arch Linux, combined with a personal project named OrangeJS which runs javascript at runtime.
Its a multi-purpose tool that allows you to configure wifi settings, bluetooth transmission, Reverse-engineering tools, Games, SSH and a proxy list for web browsing. (More comes soon)
