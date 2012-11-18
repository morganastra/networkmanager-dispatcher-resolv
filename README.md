NetworkManager-dispatch script for resolv.conf
==============================================

This is a script to make NetworkManager add the contents of resolv.conf.head and resolv.conf.tail around the auto-generated resolv.conf.

See the ArchWiki articles on [resolv.conf](https://wiki.archlinux.org/index.php/Resolv.conf) and the [NetworkManager dispatcher](https://wiki.archlinux.org/index.php/NetworkManager#Network_services_with_NetworkManager_dispatcher) for more information.

The NetworkManager page also has a [section](https://wiki.archlinux.org/index.php/NetworkManager#NetworkManager_prevents_DHCPCD_from_using_resolv.conf.head_and_resolv.conf.tail) on resolv.conf; this script is adapted from the one presented there.
