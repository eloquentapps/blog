---
layout: post
title:  Introducing Eloquent Store
date:   2016-07-08 20:49:00
---
Hello world,

Welcome to the Eloquent Store Blog.

Now, you're probably wondering what [Eloquent Store](https://eloquentstore.com) is. Put simply, Eloquent Store is a universal app store for Linux that provides apps as a single file that can run on every distribution. Eloquent Store is a browser based store, which means it can run on any Linux distribution with a web browser without having to install any software. Eloquent Store aims to solve the following problems in the Linux ecosystem.

- Provide Linux users with a single place to download and buy Linux apps for any distro, without needing to have any software pre-installed on their system.
- Provide Linux developers with a platform to host their apps, and distribute them to the entire Linux platform with a single package, and in a single place.

I have been a Linux and Mac user for many years (now 100% Linux user), and I've always found it frustrating to find and install software on any distro. Yes, we have amazing package managers that contain 90% of the software that I want to install, but these are rarely maintained by the actual developer of that software as most developers just don't have the time to package their app 100 times to support Linux.

This problem has been solved for a long time with a solution called [AppImage](http://appimage.org), and more recently with [Snaps](http://snapcraft.io) and [Flatpak](http://flatpak.org). These solutions allow you to package your app once and run it on any Linux distribution.

The solution we chose to use is AppImage because it is based on the concept of 1 app = 1 file, and each AppImage should run on the target distributions without any "runtime" software to be installed on the users system and without requiring root access. Both snaps and flatpaks require root access and runtime software to be installed on your system, meaning by default, these systems do not "just work" as AppImage does.

There is currently a divide between Snaps and Flatpaks, Ubuntu are pushing their snaps system, and Fedora is pushing their Flatpak system. This means that Ubuntu is unlikely to support Flatpaks by default, and Fedora is unlikely to support snaps by default, so either the developer still has to package for multiple platforms, or the user has to figure out how to run these apps by themselves. AppImages just work!

We are very close to releasing a public beta of Eloquent Store and we would love to hear from you about how we can all make Linux the best platform for both developers and end-users.

If you would like to get in touch about being one of the first apps to be featured in Eloquent Store, then please contact me on [chris@nimbusoft.co.uk](mailto:chris@nimbusoft.co.uk).

Chris
