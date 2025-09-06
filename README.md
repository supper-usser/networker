<h5> networker is a simple Bash script to quickly switch between Home and Work network configurations on a Linux system using /etc/network/interfaces.

  ⚙️ Usage
./networker [-h | -w]


Options

-h → Apply Home configuration (DHCP on eth0). \br
-w → Apply Work configuration (Static IP on eth0).

⚠️ When selecting the -w option, you may need to run the script twice for changes to fully apply.
If no option is provided, the script shows usage instructions and exits.


📋 Requirements

Linux system using /etc/network/interfaces (e.g., Debian, Ubuntu with ifupdown).
Root privileges (script modifies /etc/network/interfaces and /etc/resolv.conf).
systemctl for restarting networking service.
