##        OpenSUSE TumbleWeed SonicDE-workspace rpms
You will find SonicDE-workspace and SonicDE-workspace-lang
in the x86 repo and the SonicDE-*.src.rpm in SRPMS. The main
workspace rpm contains languages for 90+% of computer users worldwide while the lang package contains the rest and is an optional addon package.

## While these packages "work for me" I would recommend trying them in a VM first to verify. Consider these to to testing/beta rpms.

1. Install sonicDE-workspace. Zypper/KDE will probably complain
that you are overwriting files. Just say yes. The sonic-workspace-lang file is optional.

2. The rpms will also write two files to /etc/profile.d/ named sonicDE.sh and sonicDE.csh based on the file found in build-dir/prefix.sh in the sources. They will be run next time you login.
Logout and back in again after installing.

3. Have fun testing!!






