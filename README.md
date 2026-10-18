# DevOps Linux Fundamentals - Day 7 Machine Test

Hands-on Linux test covering package management, storage analysis, mounting and filesystems, backup and compression, and a production troubleshooting challenge, followed by theory questions.

## Structure

```
README.md
answers/
  answers.md                                        # commands + explanations for all parts
  DevOps-Linux-Fundamentals-Day7-Machine-Test.pdf   # original test document with answers
screenshots/
  part1-*.png ... part5-*.png                       # terminal screenshots for each part
```

## Topics covered

| Part | Topic | Key commands |
|------|-------|--------------|
| 1 | Package Management | `apt update`, `apt install`, `apt search`, `apt show`, `apt remove` |
| 2 | Storage Analysis | `df -h`, `du -sh`, `lsblk`, `blkid`, `fdisk -l` |
| 3 | Mounting & Filesystem Management | `mount`, `/etc/fstab`, `mkdir /mnt/...` |
| 4 | Backup & Compression | `tar`, `gzip`, `zip`/`unzip`, `rsync` |
| 5 | Production Troubleshooting | `df`, `du`, `lsblk`, `apt autoremove`, `rsync` |

## Environment

- Ubuntu on WSL2 (Windows Subsystem for Linux)
