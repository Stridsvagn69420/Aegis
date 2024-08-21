# Aegis
Encrypted DNS server and stub resolver

This project aims to be both a DNS server with the ability to filter like Pi-Hole and AdGuard Home while also providing a stub resolver for Linux supporting these extra protocols:
- DNS over TLS
- DNS over HTTPS (HTTP/1.1 and HTTP/2)
- DNS over QUIC
- DNS over HTTPS3

The stub resolver shall be analogous to `systemd-resolved`, whereas the DNS server does what Pi-Hole and AdGuard Home can do, but with its focus on encrypted DNS.
