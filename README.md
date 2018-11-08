# Netctl-dispatcher script for Chrony

This repository provides a hook that can automatically notify the
[Chrony](https://chrony.tuxfamily.org/) of the new network state. You
can use it by installing the `chrony-dispatcher` script from this
repository into `/etc/netctl/hooks/`.

**Note:** I personally moved on from using chrony to systemd-timesyncd.
As such, this script is no longer being tested, but I assume it still
works.
