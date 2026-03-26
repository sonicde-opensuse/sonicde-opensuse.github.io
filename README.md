## OpenSUSE TumbleWeed SonicDE-workspace rpms
You will find SonicDE-workspace and SonicDE-kwin-x11
in the x86 repo and the SonicDE-workspace/kwin.src.rpms in SRPMS. The main workspace rpm contains languages for 90+% of computer users worldwide while the lang package contains the rest and is an optional add-on package. Workspace and Kwin should also pull in their respective *.lib packages. Please add them if they do not.

## This is the initial version of SonicDE-workspace-Plasma-6.5.   
When KDE-Plasma-6.6 is updated on TumbleWeed I will package the   latest version of SonicDE. As always testing in a VM initially is prudent but that being said they "work for me" on my everyday desktop. They have also been tested on an ancient Toshiba Satellite laptop.   

1. Install sonicDE-workspace/kwin-x11. Zypper/KDE will probably complain
that you are overwriting files. Just say yes. 

2. The sonic-workspace/kwin-lang and devel files are optional.

3. Have fun testing!!






