# Hytale Invite Decoder

A browser-based tool for decoding Hytale invitation codes to help players connect to client-hosted servers.

## Purpose

When hosting a Hytale server from the game client, you receive an invitation code to share with friends. This tool decodes that invitation code to reveal important server connection details, which is especially useful for:

- **Port Forwarding Setup**: Identify the exact port number you need to forward in your router settings
- **Confirming Server Settings**: Verify your server name, host name, and connection details are correct
- **Troubleshooting Connections**: Check the IP address and port information when friends have trouble connecting
- **Network Configuration**: Understand the connection parameters needed for your specific network setup

## How to Use

1. Copy your Hytale server invitation code
2. Paste it into the decoder
3. View the decoded information including:
   - Server Name
   - Host Name
   - IP Address (for local network identification)
   - Port (crucial for port forwarding)

## Features

- **Instant decoding** - Works entirely in your browser, no server required
- **Privacy-focused** - All processing happens locally, your codes never leave your device
- **No installation** - Just visit the page and paste your code
- **Complete data view** - See both highlighted key fields and the full raw JSON data

## Technical Details

The invitation code is a base64-encoded, zlib-compressed JSON object containing server connection metadata. This decoder extracts and displays that information in a user-friendly format.
