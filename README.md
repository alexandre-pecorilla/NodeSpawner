# NodeSpawner

*Simple scripts to quickly and easily deploy nodes of all kinds:*

- Bitcoin & Lightning
- Monero
- Tor
- VPN (OpenVPN/Wireguard)
- SimpleX (SMP)
- Jabber (XMPP)
- Matrix
- Mail (SMTP/IMAP/POP3)
- SearXNG
- ...

The goal is to make it easier to support decentralized networks and use self-hosted open-source tech.

Recommendations:

1. Use the [Tor Browser](https://www.torproject.org/download/)
2. Find a privacy oriented VPS provider like [Njalla](https://njallalafimoej5i4eg7vlnqjvmb6zhdh27qxcatdn647jtwwwui3nad.onion/)
3. Register with XMPP OMEMO (get a free account [here](https://5july.org/jabber/) and use an OMEMO-compatible client like [Gaijin](https://gajim.org/))
5. Pick a small VPS with a recent version of Debian/Ubuntu x64
6. Pay with [Monero](http://monerotoruzizulg5ttgat2emf4d6fbmiea25detrmmy7erypseyteyd.onion)
7. Use `torsocks` to SSH in the VPS
8. Change the default SSH port and only allow key authentication (disable password authentication)
9. Don't setup a firewall, the scripts take care of it and only expose what's needed
10. Run no more than one script per VPS (we prefer small single purpose VPS)
11. Keep your OS and programs up to date

## List of scripts

### tor_relay_debian_ubuntu.sh
Spawns a fully operational Tor Middle/Guard relay and provides you with your relay's fingerprint and your [Tor Relay Search](http://hctxrvjzfpvmzh2jllqhgvvkoepxb4kfzdjm6h7egcwlumggtktiftid.onion/rs.html) listing.
