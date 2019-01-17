
A Macintosh II emulator that runs A/UX (and A/UX only). 

Shoebill is an all-new, BSD-licensed Macintosh II emulator designed from the ground up with the singular goal of running A/UX. 

Shoebill requires a Macintosh II, IIx or IIcx ROM, and a disk image with A/UX installed.

[Download the latest release], and then see the [getting started] wiki.  
Also check out [screenshots].

__Update (Jan 16th, 2019)

__I've decided to fork Shoebill to continue work on this emulator to see if I can implement some of the missing features and work on some of the existing bugs. I'm new to programming, so don't expect any releases any time soon, but if I have any news, I'll post it here. .__

#### Supports
* A/UX 1.1.1 through 3.1 (and 3.1.1 a little)

#### Currently Implements
* 68020 CPU (mostly)
* 68881 FPU (mostly)
* 68851 PMMU (just enough to boot A/UX)
* SCSI
* ADB
* PRAM
* Ethernet (via emulated Apple EtherTalk/DP8390 card)
* A NuBus video card with 24-bit depth. 

#### Does not implement (yet)
* Sound
* Floppy
* Serial ports

    
[Download the latest release]:https://github.com/kgllewellyn/Shoebill/releases
[getting started]:https://github.com/kgllewellyn/Shoebill/wiki/Getting-Started
[screenshots]:https://github.com/kgllewellyn/Shoebill/wiki/Screenshots
[The thread on emaculation.com]:http://www.emaculation.com/forum/viewtopic.php?f=7&t=8288

