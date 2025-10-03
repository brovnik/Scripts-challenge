## Script 1 - QUIP

**Quickly check IPv4, IPv6, and MAC. You can copy them one at a time to the clipboard**

### Setup
1. Place `quip` script in a directory in your `$PATH` (e.g. `/usr/local/bin` or `/usr/bin`).  
2. Make it executable with
   ```bash
   sudo chmod +x /usr/local/bin/quip
   ```
3. Make sure your system has one of the following clipboard tools installed: **xclip** or **xsel**, depending on your distro.
  ```bash
   # For Debian-based distros
   sudo apt install xclip
   
   # For RHEL-based distros
   # Enable the EPEL repository to access additional packages, like xsel
   sudo dnf install epel-release
   sudo dnf install xsel
   
   # For Arch-based distros
   sudo pacman -Syu xclip
   ```

### Usage
   ```bash
   quip <option>
   
   # example
   quip -6
   quip -m
   ```
| Flag | Description                           |
|------|---------------------------------------|
| \-4\ | Save IPv4 to clipboard                |
| \-6\ | Save IPv6 to clipboard                |
| \-m\ | Save MAC to clipboard                 |
| \-a\ | Display all of the above in terminal  |

### Supported Distributions by Family

**Debian:** Debian, Ubuntu, Linux Mint
**RHEL:** RHEL, CentOS, AlmaLinux
**Arch**: Arch Linux
