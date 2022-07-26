- 👋 Hi, I’m @kaliroman
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
kaliroman/kaliroman is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

Hello guys
Iam trying use fern wifi cracker in kali/linux(kali-linux-2022-W30-virtualbox-amd64) with usb wlan adapter TL-WN722N/v2 and there are ERROR CODES following me everywhere.
I have following problem, i did every step here :

    sudo apt update
    sudo apt upgrade
    sudo apt-get dist-upgrade
    reboot
    sudo apt-get install linux-headers-$(uname -r)
    sudo apt install bc
    sudo apt-get install build-essential
    sudo apt-get install libelf-dev
    sudo apt install dkms
    sudo rmmod r8188eu.ko
    git https://github.com/drygdryg/rtl8188eus (This works for me 😂)
    cd rtl8188eus
    sudo -i
    echo 'blacklist r8188eu'|sudo tee -a '/etc/modprobe.d/realtek.conf'
    reboot
    cd rtl8188eus
    sudo make && make install
    reboot
    
when i type command:

sudo make && make install

This error codes show up here:
https://user-images.githubusercontent.com/109991163/181126062-5c1ddd0f-e3e2-4785-afc4-ef70a31b02d7.jpg

I could not install driver rtl8188eus for my usb wlan adapter TL-WN722N/v2. This means i can not use Fern WiFi Cracker.
Can u help me with this ?
