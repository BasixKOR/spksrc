SPK_NAME = arp-scan
SPK_VERS = 1.9.8
SPK_REV = 1

DEPENDS = cross/arp-scan

MAINTAINER = hgy59
DESCRIPTION = Command-line tool for system discovery and fingerprinting. It constructs and sends ARP requests to the specified IP addresses, and displays any responses that are received. 
DISPLAY_NAME = arp-scan
STARTABLE = no

HOMEPAGE = http://www.royhills.co.uk/wiki/index.php/Arp-scan_User_Guide
LICENSE  = MIT

SPK_COMMANDS = bin/arp-scan 
# perl script (works only when perl package is installed)
SPK_COMMANDS += bin/arp-fingerprint

include ../../mk/spksrc.spk.mk
