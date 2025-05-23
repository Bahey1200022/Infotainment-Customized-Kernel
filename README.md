# Infotainment-Customized-Kernel

Infotainment-customized-kernel

🛠️ Raspberry Pi 4 Kernel Customization Project

This project introduced me to kernel customization using the Yocto Project, where I built a tailored Linux distribution for the Raspberry Pi 4. Throughout the process, I explored:

Kernel Customization: Modifying the kernel configuration to meet project-specific requirements.
Recipe Development: Writing package and image recipes while ensuring proper dependency resolution.
Distro Configuration: Creating custom distributions with distinct init systems and feature sets.
Yocto Project Proficiency: Gaining hands-on experience with Yocto's build process, metadata layers, and BitBake workflows.

🌟 System Features

Init System: Systemd as the primary init system for efficient service management.
Remote Access: Secure Shell (SSH) for remote administration.
Connectivity: Full support for Wi-Fi and Bluetooth.
Development Tools: Nano text editor for convenient on-device editing.
Graphical Interface: Qt5 integration for GUI-based applications.
Audio Support: ALSA utilities and PulseAudio for comprehensive sound control.
Peripheral Control: WiringPi for GPIO, SPI, and I2C interaction.
Customizable Distro: Two build variants, each with different init systems.
added vsomeip cpp package 
Special thanks to Hazem Khaled for an insightful walkthrough on OS customization—from manually building each core component from scratch to leveraging Yocto for automated builds.

💡 Below is a demo showcasing each feature in action...

[Screencast from 02-20-2025 01:08:53 PM.webm](https://github.com/user-attachments/assets/05dd1206-8951-4bce-b3e1-8ae0f0e43611)

Yocto Layers :
![image](https://github.com/user-attachments/assets/19739cf1-947a-442b-94bc-8e879aa17114)

Distros :
![image](https://github.com/user-attachments/assets/2f7c658a-5637-4f18-87e7-db8e6f4d35f5)

![image](https://github.com/user-attachments/assets/35c4f513-3a98-44a9-bc6c-e10ebd9da6c9)

Final Image :
![image](https://github.com/user-attachments/assets/d0e43cdb-b4db-4d8d-98ec-9eced118715a)



