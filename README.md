# Scripts-challenge

## Script 1 - QUIP

**Quickly check IPv4, IPv6, and MAC. You can copy them one at a time to thw clipboard**

### Setup
1. Place the `quip` script in a directory in your `$PATH` (for example: `/usr/local/bin` or `/usr/bin`).  
2. Make it executable:
   ```bash
   sudo chmod +x /usr/local/bin/quip
   ```
3. Make sure your system has one of the following clipboard tools installed: xclip or xsel, depending on your distro.
quip <flags>:
-4 Save IPv4 to clipboard
-6 Save IPv6 to clipboard
-m Save MAC to clipboard
-a Display all of the above in terminal

### Usage
   ```bash
   quip <option>
   ```

   -4   Copy the IPv4 to the clipboard
   -6   Copy the IPv6 to the clipboard
   -m   Copy the MAC to the clipboard
   -a   Display all in terminal (IPv4, IPv6, MAC)

### Supported Distributions by Family

**Debian:** Debian, Ubuntu, Linux Mint
**RHEL:** RHEL, CentOS, AlmaLinux
**Arch:** Arch Linux
