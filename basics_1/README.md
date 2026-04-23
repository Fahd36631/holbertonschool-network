# Basics 1 - Network Configuration

This directory contains tasks about host and DNS-related network configuration.

## Task: 0-change_your_home_IP

The script `0-change_your_home_IP` updates `/etc/hosts` with the required mappings:

- `localhost` resolves to `127.0.0.2`
- `facebook.com` resolves to `8.8.8.8`

The script is intended to be run with `sudo` because it writes to `/etc/hosts`.
