---
title: Linux Stuff
date: 2018-8-6 8:33:55 +0000
tags: [linux]
---

* to set proper time on ubuntu server (18.04)..

select the proper time zone with...
```
sudo dpkg-reconfigure tzdata
```

then sync the hardware clock and system clock
```
sudo hwclock --systohc
```



* to install zeroconf networking that will resolve and broadcast hostnames (ubuntu 18.04)

```
sudo apt-get install avahi-daemon avahi-discover avahi-utils libnss-mdns mdns-scan
```
