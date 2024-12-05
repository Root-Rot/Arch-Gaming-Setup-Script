# Arch-Gaming-Setup-Script
Arch Gaming Setup Script

This is a simple script to set up your Arch system for gaming. It installs GameMode and a few choice applications, along with a custom kernel.

Custom Kernel Used:
linux-cachyos

Installed Packages:
steam
protonplus
gamemode
power-profiles-daemon
heroic-games-launcher-bin
lutris
lutris-wine-meta
bottles
grub-customizer
yay

Notes:
1. Make sure to select the linux-cachyos kernel in GRUB Customizer, save the configuration, and reboot your system after running the script.
2. For GameMode to work, ensure your system's CPU governor is set to performance, and run gamemoded -t to test if it is working properly. The power-profiles-daemon should provide this option under Power Options in the settings on both GNOME and KDE.
