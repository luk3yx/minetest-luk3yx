# luk3yx's unofficial Minetest snap
This is my unofficial Minetest snap package, derived from the Minetest snap in the snappy playpen.

## How to install
**Using sudo: (Ubuntu & Derivatives)**
~~~
$ sudo snap install minetest-luk3yx
~~~

**Using su:**
~~~
$ su -c 'snap install minetest-luk3yx'
~~~


Note: Make sure that snapd is installed before running the above commands.

## FAQ
**What is a snap?**

Snaps are universal Linux packages.

**Where can I find a forum page for this?**

You can find it [here](https://forum.minetest.net/viewtopic.php?f=42&t=16088).

**How do I install snapd?**

Debian, Ubuntu, and Ubuntu derivatives:
~~~
sudo apt install snapd
~~~


OpenSuse:
~~~
sudo zypper addrepo http://download.opensuse.org/repositories/system:/snappy/openSUSE_Leap_42.2/ snappy
sudo zypper install snapd
~~~


Arch Linux:
~~~
sudo pacman -S snapd
sudo systemctl enable --now snapd.socket
~~~


More:
[http://snapcraft.io/docs/core/install](http://snapcraft.io/docs/core/install)

Credit to [http://snapcraft.io](http://snapcraft.io) for the resources shown in the FAQ.
