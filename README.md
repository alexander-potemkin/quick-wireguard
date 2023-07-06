# WireGuard installer

Opionated installer based on original [angristan work.](https://github.com/angristan/wireguard-install/issues) 

## Requirements

Supported distributions:
- Debian >= 10
- Ubuntu >= 18.04

## Usage

```bash
curl -O https://raw.githubusercontent.com/alexander-potemkin/quick-wireguard/master/wireguard-install.sh
chmod +x wireguard-install.sh && sudo ./wireguard-install.sh
```

`sudo ./wireguard-install.sh` to add or remove clients, or remove WireGuard from the server.
