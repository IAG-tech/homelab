# SSH SETUP

⚠️ This is the v0.1 minimal functional setup. Full step-by-step setup and troubleshooting will be added in later versions.

----

## 🎯 What/Why

The first step when turning a raspberry that we want to convert into the first version of a homelab is install a operating system  and enable remote access.
In my case, I installed **Raspberry Pi OS Lite** and configured **SSH access** because I dont have a monitor or keyboard connected to the Pi - so remote login is required.

SSH provides me a secure way to manage the system remotly from my laptop. Later I will improve its security with other practices such as ssh keys, firewall rules and VPN access - those steps will be covered in the [SSH-Hardening-v0.1](SSH-Hardening-v0.1.md)

-----

##  ⚙️ Quick Steps

1. Flash Raspberry Pi OS Lite to micro SD card with **Raspberry Pi Imager**.
2. Create empty **ssh file** in the boot partition.
3. Boot the Raspberry Pi and connect to the network (ethernet recommended).
4. Find **IP address**.
5. Connect via SSH from laptop with the passwor of the Raspberry Pi. By default the password is "raspberry"
-----

## ✅ Verification

To verify the ssh is working try connecting Raspberry Pi via SSH with the command
```bash
ssh pi@192.168.10.70 
```

If the login succeeds, SSH access is enabled correctly.


