##        OpenSUSE TumbleWeed SonicDE-workspace rpms
You will find SonicDE-workspace and SonicDE-workspace-lang
in the x86 repo and the SonicDE-*.src.rpm in SRPMS. The main
workspace rpm contains languages for 90+% of computer users worldwide while the lang package contains the rest and is an optional addon package.

## This is the initial version of SonicDE-workspace-Plasma-6.5.   
When KDE-Plasma-6.6 is updated on TumbleWeed I will package the   latest version of SonicDE. As always testing in a VM initially is prudent but that being said they "work for me" on my everyday desktop. They have also been tested on an ancient Toshiba Satellite laptop.   

1. Install sonicDE-workspace. Zypper/KDE will probably complain
that you are overwriting files. Just say yes. The sonic-workspace-lang file is optional.

2. The rpms will also write two files to /etc/profile.d/ named sonicDE.sh and sonicDE.csh based on the file found in build-dir/prefix.sh in the sources. They will be run next time you login.
Logout and back in again after installing.

3. Have fun testing!!






