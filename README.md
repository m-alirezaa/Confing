# V2ray Configuration Guide

Welcome to the V2ray Configuration repository! This repository contains configuration files for various V2ray protocols in both client and server setups.

## 📁 Repository Structure

```
config/
├── client_config.json      # VMess Client Configuration
├── client_vless.json       # VLESS Client Configuration
├── client_trojan.json      # Trojan Client Configuration
├── client_shadowsocks.json # Shadowsocks Client Configuration
├── server_config.json      # VMess Server Configuration
├── server_vless.json       # VLESS Server Configuration
├── server_trojan.json      # Trojan Server Configuration
└── server_shadowsocks.json # Shadowsocks Server Configuration
```

## 🚀 Quick Start

### Client Setup
1. Download the appropriate client configuration from the `config/` folder
2. Update the server address, port, and authentication credentials
3. Load the configuration into your V2ray client

### Server Setup
1. Download the server configuration from the `config/` folder
2. Configure your server settings (port, credentials, etc.)
3. Run V2ray with the configuration

## 📋 Available Configurations

### Client Configurations
- **VMess Client** - Connect to VMess servers (UUID-based)
- **VLESS Client** - Connect to VLESS servers (lightweight)
- **Trojan Client** - Connect to Trojan servers
- **Shadowsocks Client** - Connect to Shadowsocks servers

### Server Configurations
- **VMess Server** - Host a VMess server
- **VLESS Server** - Host a VLESS server
- **Trojan Server** - Host a Trojan server
- **Shadowsocks Server** - Host a Shadowsocks server