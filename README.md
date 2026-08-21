# Fedora Homelab

Documentation of a Fedora Linux workstation configured as a small self-hosted lab environment.

The project was built to develop practical experience with Linux administration, networking, containerization, DNS, firewall configuration, and systematic troubleshooting.

## Hardware

- System: Acer Aspire A315-24P
- CPU: AMD Ryzen 3 7320U
- RAM: 8 GB
- Storage: 150 GB
- Network: Wi-Fi

## Objectives

- Install and configure Fedora Linux as a daily-use workstation
- Develop practical Linux administration skills
- Troubleshoot network connectivity through the command line
- Understand DNS resolution and configuration
- Configure and inspect firewall behavior
- Deploy containerized services
- Understand Docker networking and port mappings
- Document troubleshooting procedures and resolutions

## Environment

| Component | Configuration |
|---|---|
| Operating System | Fedora Workstation |
| Network | Wi-Fi |
| Network Management | NetworkManager |
| Container Platform | Docker |
| Container Management | Docker Compose |
| DNS Service | Pi-hole |
| Remote Access | Tailscale |

## Networking

The system was configured and troubleshot using Linux command-line tools including:

- `nmcli`
- `ip`
- `ping`
- `tracepath`
- `resolvectl`
- `ss`
- `firewall-cmd`

Documentation:

- [NetworkManager](networking/networkmanager.md)
- [DNS](networking/dns.md)
- [Firewall](networking/firewall.md)

## Docker

Docker was configured to host self-hosted services on the Fedora system.

The project includes experience with:

- Docker containers
- Docker Compose
- Port mappings
- Container networking
- DNS configuration
- Firewall interaction

Documentation:

- [Docker Overview](docker/README.md)
- [Pi-hole](docker/pi-hole.md)

## Troubleshooting

The project includes documented troubleshooting cases involving:

- Wi-Fi connectivity
- Network configuration
- DNS resolution
- Routing
- Firewall configuration
- Docker networking
- Container port mappings

See the [troubleshooting](troubleshooting/) directory for individual case studies.

## Demonstrations

Selected configuration and troubleshooting processes are demonstrated through screen recordings.

See [Videos](videos/README.md).

## Skills Demonstrated

- Fedora Linux
- Linux CLI
- NetworkManager
- TCP/IP
- DNS
- Routing
- Firewalls
- Docker
- Docker Compose
- Pi-hole
- Tailscale
- Network troubleshooting
- System administration
- Technical documentation
