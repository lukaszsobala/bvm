# bvm
Windows 11 Virtual Machine on ARM Linux

I'm so excited to share this with you once it's ready. A W11 VM on a Pi has been something I have wanted, and tried, to do for about 4 years. Until this month my attempts always ended in failure.  
The project is progressing well. So far we have around 700 lines of shell script, and counting. Probably going to do a CLI script and a GUI frontend, like what I did with wor-flasher.  

If you know QEMU or have experience with Windows autounattend.xml, I would like to ask for your ongoing help once this is live to help build out more features. You just know somebody will want to do serial passthrough, bluetooth passthrough, or something really specific that I will have no idea how to implement.

GPU driver: Full 2D/3D acceleration may be possible. First of all if you are Jeff Geerling and have a secondary GPU connected to your Raspberry Pi, in theory Windows could talk to it using GPU passthrough. Maybe.  
For everyone else, it may be possible using this unfinished series of PRs spanning multiple projects: https://github.com/virtio-win/kvm-guest-drivers-windows/pull/943 Also see https://wiki.archlinux.org/title/QEMU/Guest_graphics_acceleration#Virgil3d_virtio-gpu_paravirtualized_device_driver  
If someone reading this is actually good with "real programming languages," instead of only knowing shell script like myself, feel free to compile it and check if it works on ARM.

Nothing here yet. :)
![bvm-wallpaper](https://github.com/user-attachments/assets/81bbf5d7-a443-4da1-9111-60f0626c034c)
![20250221_02h33m45s_grim](https://github.com/user-attachments/assets/e310dd9b-e444-4d6c-9dac-caa76f3aaf26)
