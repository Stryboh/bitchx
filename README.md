# BitchX IRC Client Package

This package contains a pre-compiled version of BitchX IRC client with all plugins, linux-x86-64.

## Installation

Run the installation script:
```bash
chmod +x install.sh
./install.sh
```

## Usage

Start BitchX:
```bash
~/bin/BitchX
```

### Basic Commands

- Connect to a server: `/server server.address`
- Join a channel: `/join #channelname`
- Set your nickname: `/nick your_nickname`
- Send a private message: `/msg nickname message`
- List channels: `/list`
- Get help: `/help`

### Default Configuration

The installation script creates a default configuration file at `~/.BitchX/config` with the following settings:
- Default server: efnet.deic.eu
- Default nickname: your username
- Default user modes: +i (invisible)
- Default channel modes: +nt (no external messages, topic protection)

You can modify these settings by editing the config file.

## Plugins

The following plugins are included:
- europa: Database-backed knowledge base
- abot: Auto-reply bot
- arcfour: Encryption
- blowfish: Encryption
- fserv: File server
- And more...

## Support

For more information, visit the BitchX website or IRC channel. 
