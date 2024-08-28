# TrueNAS Scale improve Guide

> [!NOTE]
> This guide is currently being written

## Foreword to this guide

The guide I've written here is intended for users who, like me, want to go further with their TrueNAS server.

I wrote this guide because I was really fed up with the TrueNAS founders taking their users for fools and forbidding them to use their OS to the full. Unimaginable but true, the IXSystem team forbids you to do certain things on your TrueNAS Scale under the stupid pretext of “not breaking your server”, except that if you're here it's because you wanted to go beyond the limits imposed by TrueNAS just like I did to see how to remove all the stupid limitations of TrueNAS Scale and perosnalize it to your own desires.

Just like the bullshit that Team TrueNAS can post about the risk of breaking your NAS, I'm going to show you here in this guide only things tested by me that have indeed allowed me to know what can break your NAS or not and that are “safe” to use.

If you use True NAS Core, unfortunately this guide is not for you, I used True NAS Core a long time ago and I never want to touch that crap again, FreeBSD users are probably mazochists who love being tortured.

## Limitation of liability

> [!CAUTION]
> I cannot be held responsible for the loss of your data should you perform any untoward action. If you look at this guide, it is because you fully assume the risks of going beyond the limits imposed by TrueNAS.

# Table of contents

- [Remove all unnecessary stuff from TrueNAS Scale]()
- [Re-enable Aptitude command]()
- [Customize the TrueNAS web interface theme]()
- [Customize NGINX configuration]()
- [Disable TrueNAS RootFS protection]()
- [Delete Kubernetes and replace with Docker]()
