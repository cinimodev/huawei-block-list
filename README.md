# huawei-block-list

## PiHole Update
This is a fork from [huawei-block-list](https://github.com/deep-bhatt/huawei-block-list) with the blocklist syntax updated to work in PiHole. Below is the original notes from the creator on how they captured the blocklist.

## What is this? 
It's a block list. You can integrate this into your PiHole or local blocking software such as Blokada, AdAway... etc. to block out all the outgoing connections to the said domains.

## Why do i need this?
It turns out, if your device has bloated softwares(ie. Apps that comes pre-installed and you can't remove them unless you root your device, you're forced into keeping those services running. Manufacturers like Huawei have stopped providing bootloader unlock codes thereby not allowing you to root your device. So, the best solution is to setup a local proxy server that blocks the connection. 

## Captured with Blockada

I've collected these subdomains by using Blockada for several months &  adding each entry manually. These should block all(i hope?) the outgoing connection to huawei servers. I'll keep updating this list as i discover more domains.

## How to contribute?

If you've got more domains to add to this list, please put up an issue. 

## recommended hosts to whitelist
1. To allow EMUI updates, I've commented(ie.excluded from blocklist) `query.hicloud.com` and `configserver.platform.hicloud.com`. Free feel to uncomment them if needs be.
