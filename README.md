# iOSJailBreakBasedOnProjectZero
I updated the exploit code by Project Zero to run on devices that I own. Deleted the previous repo and pushing in new one with no obfuscation.


So, Ian Beer from Project Zero came up with a working root exploit for iOS 10.1.1 and submitted the details for it at https://bugs.chromium.org/p/project-zero/issues/detail?id=965. This is not a Jailbreak per-se, but does give us a root shell on the iOS device. The exploit was written for iPod touch 6g and iPad mini 2 running 10.1.1. Direct link to the exploit is https://bugs.chromium.org/p/project-zero/issues/attachment?aid=263891

On the basis of the provided details - I’ve reversed the iOS 10.1 and 10.1.1 kernel firmware to calculate the required offsets for iPhone 7 Plus running iOS 10.1 + iPhone 6s running 10.1.1 and updated the exploit accordingly to run well on these devices.

The steps to compile my updated exploit code is pretty much the same as mentioned in the original bug report. 
