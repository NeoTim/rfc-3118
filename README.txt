Notes
-----

In order to support DHCP FORCERENEW message, the protocol implementation MUST
implement DHCP-AUTH.

Windows DHCP client and server does not have DHCP-AUTH support.

Hence it wont be possible for the Windows DHCP client to accept FORCERENEW
messages.

Links
-----

https://wiki.infinetwireless.com/pages/viewpage.action?pageId=10781285

https://github.com/daniel-dinu/DHCPAuth-patch

https://github.com/daniel-dinu/DHCPAuth

https://roy.marples.name/projects/dhcpcd (supports DHCP authentication)

http://www.rjsystems.nl/en/2100-dhcpv6-stateful-autocfg.php

http://klub.com.pl/dhcpv6/snapshots/ (DHCPv6: Dibbler - a portable DHCPv6)
