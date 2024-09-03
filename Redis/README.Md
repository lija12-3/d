# Redis Connection and Authentication Guide

## Overview

This guide provides instructions for connecting to a Redis server using the `redis-cli` tool, authenticating with a password, and verifying the connection.

## Prerequisites

- Ensure that Redis is installed and running on your server.
- Ensure that `redis-cli` is installed on your client machine.

## Connect to Redis Using `redis-cli`

1. **Open a Terminal Window** on your client machine.

2. **Run the `redis-cli` Command**:
   Replace `127.0.0.1` with the IP address of your Redis server and `6379` with the port number if it is different.
   ```bash
   redis-cli -h 127.0.0.1 -p 6379

AUTH your_secure_password_here

Verify Authentication
Run the PING Command: After successful authentication, you can run Redis commands to verify the connection.

PING
Check the Response: If everything is working correctly, you should receive a PONG response.


