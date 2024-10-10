# Server Connection Helper

This repository contains a Fish shell function that helps manage and connect to multiple servers with different users and credentials. It provides a simple way to view available combinations for SSH connections.

## Overview

The `connect_servers` function allows you to quickly identify the SSH commands needed to connect to your servers, accommodating various user credentials and server metadata such as IP addresses and domain names.

### Features
- List available SSH connection options based on predefined users and servers.
- Outputs placeholders for SSH commands to be customized as needed.

## Prerequisites

- Fish shell installed on your system.
- Basic understanding of Fish shell syntax and commands.

## Installation

1. Clone this repository to your local machine:

   ```bash
   git clone <repository_url>
   cd <repository_directory>
