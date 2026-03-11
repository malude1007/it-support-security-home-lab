# Environment Setup

## Date
2026-03-11

## Objective
Prepare the Linux virtual machine for an IT support and security lab.

## Actions Completed
- Renamed the virtual machine to `IT-LINUX-LAB`
- Changed the Linux hostname to `IT-LINUX-LAB`
- Updated `/etc/hosts` to reflect the new hostname
- Rebooted the system to apply the hostname change
- Verified the hostname from the terminal

## Commands Used
- `sudo hostnamectl set-hostname IT-LINUX-LAB`
- `sudo nano /etc/hosts`
- `hostnamectl`
- `hostname`

## Notes
Using a clear hostname makes the lab look more organized, improves documentation quality, and keeps screenshots professional.
