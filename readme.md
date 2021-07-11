This script specifically disables Windows Defender in Windows 10.
This can occasionally be useful when wishing to avoid overhead during benchmarking or for low-latency applications like audio hosts.

It WILL get incorrectly detected as potential malware by many antivirus programs, presumably because there is some batch script malware out there that deliberatly disables windows defender without the user knowing. Understand this before you download.

win10_disable_defender.bat disables defender, win10_enable_defender.bat re-enables it.

To run either, right-click on the file and then click on Run as Administrator. The code was originally written by https://github.com/AndyFul/
