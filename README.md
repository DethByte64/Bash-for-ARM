This Bash Binary Is A Statically Linked Binary For ARM With Networking Flags Enabled

This means you can push this to your device and it works standalone with the ability to use /dev/tcp and /dev/udp

Instructions:                                                
cd ~                                                             
git clone https://github.com/SuperDethByte/Bash-for-ARM.git            
cd Bash-for-ARM

Plug your phone into your computer.                                
Im guessing you already know how to get adb going.

adb push bash /system/bin/
