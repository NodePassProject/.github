# NodePass Project

<div align="center">
  <img src="https://cdn.yobc.de/assets/np-logo.png" alt="NodePass Logo" width="200">
  <h3>Universal TCP/UDP Tunneling Solution</h3>
  
  ![GitHub release](https://img.shields.io/github/v/release/yosebyte/nodepass)
  ![GitHub downloads](https://img.shields.io/github/downloads/yosebyte/nodepass/total)
  ![Go Report Card](https://goreportcard.com/badge/github.com/yosebyte/nodepass)
  ![GitHub last commit](https://img.shields.io/github/last-commit/yosebyte/nodepass)
  [![BSD-3-Clause license](https://img.shields.io/badge/License-BSD--3--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)
</div>

## Overview

NodePass is an advanced, lightweight TCP/UDP tunneling solution built on an innovative three-tier architecture (server-client-master). It elegantly separates control and data channels while offering intuitive zero-configuration syntax. The system excels with its proactive connection pool that eliminates latency by establishing connections before they're needed.

This repository contains components, libraries, tools, and resources related to the core [NodePass](https://github.com/yosebyte/nodepass) project.

## Main Components

### Core Components

- **NodePass Server**: The tunnel server component that accepts incoming connections
- **NodePass Client**: The tunnel client that establishes outbound connections
- **NodePass Master**: API-driven management interface for dynamic instance control

### Frontend & UI Components

- **NodePass Dashboard**: Web interface for monitoring and managing tunnel instances
- **NodePass CLI**: Command-line interface with extended functionality
- **NodePass Mobile App**: Mobile interface for on-the-go tunnel management

### Libraries & SDKs

- **NodePass Go SDK**: Official Go library for integrating with NodePass
- **NodePass JavaScript SDK**: JavaScript/TypeScript library for web integrations
- **NodePass Shell SDK**: Shell library for automation and system integration

## Key Features

### 🔀 Multiple Operating Modes

- Server mode accepting incoming tunnels with configurable security
- Client mode for establishing outbound connections to tunnel servers
- Master mode with RESTful API for dynamic instance management

### 🌍 Protocol Support

- TCP tunneling with persistent connection handling
- UDP datagram forwarding with configurable buffer sizes
- Intelligent routing mechanisms for both protocols

### 🛡️ Security Options

- TLS Mode 0: Unencrypted mode for maximum speed in trusted networks
- TLS Mode 1: Self-signed certificates for quick secure setup
- TLS Mode 2: Custom certificate validation for enterprise security

### ⚡ Performance Features

- Smart connection pooling with real-time capacity adaptation
- Dynamic interval adjustment based on network conditions
- Minimal resource footprint even under heavy load
- Automatic recovery from network disruptions

### 🧰 Simple Configuration

- Zero configuration files required
- Simple command-line parameters
- Environment variables for fine-tuning performance

## Common Use Cases

- **Remote Access**: Securely access internal services from external locations
- **Firewall Bypass**: Navigate through restrictive network environments
- **Secure Microservices**: Establish encrypted channels between distributed components
- **Database Protection**: Enable secure database access while keeping servers isolated
- **IoT Communication**: Connect devices across different network segments
- **Penetration Testing**: Create secure tunnels for security assessments

## Documentation

- [Installation Guide](https://github.com/yosebyte/nodepass/docs/installation.md)
- [Usage Instructions](https://github.com/yosebyte/nodepass/docs/usage.md)
- [Configuration Options](https://github.com/yosebyte/nodepass/docs/configuration.md)
- [API Reference](https://github.com/yosebyte/nodepass/docs/api.md)
- [Examples](https://github.com/yosebyte/nodepass/docs/examples.md)
- [How It Works](https://github.com/yosebyte/nodepass/docs/architecture.md)
- [Troubleshooting](https://github.com/yosebyte/nodepass/docs/troubleshooting.md)

## Community

- Join our [Discussions](https://github.com/yosebyte/nodepass/discussions) to share your experiences and ideas
- Follow our [Telegram channel](https://t.me/nodepass) for updates and community support

## License

This project is licensed under the [BSD 3-Clause License](/LICENCE).
