
# CIT 352: Chapter 6

```
Samuel Joshua
```

## Project 6-1

Any version of Ubuntu Server 18.04 LTS will do (e.g. Ubuntu Server 18.04.3 LTS)

### Step 9b

Insert the screen capture

<!-- TODO -->
![Alt Text](image/codingpics.jpeg

## Project 6-2

### Step 2

This is where you would add SATA disks

![add Storage](image/pics%202.jpeg

### Step 5: Typo

[Original] ``mdadm --create /dev/md0 --level=5 --raid-devices=4 /dev/sdb /dev/sdc /dev/sdd /dev/sdd --verbose``

[Corrected] ``mdadm --create /dev/md0 --level=5 --raid-devices=4 /dev/sdb /dev/sdc /dev/sdd /dev/sde --verbose``

### Step 12

Why is it not 4 GB (4 x 1 GB disks)?

<!-- TODO -->
```
The drive does not have enough space so it couldn't be evenly distribed 
```

### Step 18

Insert the screen capture

<!-- TODO -->
![Alt Text](image/pics7.jpeg

## Project 6-3

### Step 17

Insert the screen capture that shows the quota and compression configurations have been set according to the instruction.
<!-- TODO -->
![Alt Text](image/pics%204.jpeg
## Project 6-4

### Step 3: Missing instruction

- [Original]
  - At the command prompt, type ...
- [Corrected] 
  - Type `mkdir /data` to create a mount point. At the command prompt, type ...

### Step 16

Insert the screen capture

<!-- TODO -->
![Alt Text](image/pics5.jpeg

## Project 6-5

### Step 9

What are the files within these directories?

<!-- TODO -->
```
Amd64-microbde-blacklist.conf, blacklist-firewire.conf, intel-microde-blacklist.conf
Blacklist-ath_pci conf, blacklist-framebufer.conf,iwlwwifi.conf
Blacklist.conf, blacklist-rare-network.conf, mdadm.conf,Modules.conf
```

## Project 6-6

### Step 7: Correction

- [Original] `/dev/sda3`
- [Updated] `/dev/sda2`

### Step 8: Correction

- [Original] `/dev/sda3`
- [Updated] `/dev/sda2`

### Step 9: Typo

- [Original] `mount -t proc proc /proc`
- [Updated] `mount -t proc proc /mnt/proc`

### Step 11

- What warning did you receive regarding the Secret123 password?
  Bad Password: The password fails the dictionary check - it is based on a dictionary word  <!-- TODO -->

## Project 6-7

The ISO image is available at http://releases.ubuntu.com/14.04/.
Choose “64-bit PC (AMD64) server install image” for download.

### Step 26

Insert the screen capture

<!-- TODO -->
![Alt Text](image/pic6.jpeg

## Command Reference

List all new commands you learned in this chapter.

<!-- TODO -->
```
Fdisk -1
Ldvisplay
Lsblk
Poweroff
Fsck -f
Mount
Mount -t proc proc
Su-root
Journalctl -b
Ls -f
Less/proc/cpuinfo
Lshw
Lsmod
Modinfo dummy
Modprobe dummy
Lsmod | less
Ls/etc/modprobe
Vi/etc/modules-load.d/modules.conf
```

0 comments on commit 3a6c3dc
@Samueljoshua10
 
Add heading textAdd bold text, <Ctrl+b>Add italic text, <Ctrl+i>
Add a quote, <Ctrl+Shift+.>Add code, <Ctrl+e>Add a link, <Ctrl+k>
Add a bulleted list, <Ctrl+Shift+8>Add a numbered list, <Ctrl+Shift+7>Add a task list, <Ctrl+Shift+l>
Directly mention a user or team
Reference an issue, pull request, or discussion
Add saved reply
Leave a comment
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
Styling with Markdown is supported
 You’re not receiving notifications from this thread.
Footer
© 2023 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
Initial commit · byui-cit-352/chapter-6-Samueljoshua10@3a6c3dc