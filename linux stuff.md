---
title: useful linux things
date: 2018-8-6 8:33:55 +0000
tags: [linux]
---

to set proper time on ubuntu server..

select the proper time zone with...
```
sudo dpkg-reconfigure tzdata
```

then sync the hardware clock and system clock
```
sudo hwclock --systohc
```

then spin around three times while saying abacadabra and burning some sage in your left hand.

tada!
