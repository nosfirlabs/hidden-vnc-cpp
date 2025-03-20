# Hidden VNC C++ Project

## Overview

This project implements a hidden VNC (Virtual Network Computing) solution written in C++. It allows for remote desktop control with a focus on maintaining a low profile. The system consists of multiple components including a BC (Back Connection) server and client, and various supporting modules.

## Project Structure

The project is organized into several key directories:

- **VNC/** - Core VNC implementation
  - **AcDll/** - Active DLL components for VNC functionality
  - **BcClient/** - Back Connection client implementation
  - **Common/** - Shared code and utilities
  - **aplib/** - aPLib compression library integration

- **BC/** - Back Connection server components
  - **BcServer/** - Server implementation
  - **Handle/** - Connection handling
  - **Inc/** - Include files

## Features

- Remote desktop control via VNC protocol
- Back Connection functionality for NAT/firewall traversal
- Support for multiple Windows OS versions (2000 through Windows 8)
- Machine identification and authentication
- Compression using aPLib

## Building the Project

The project uses Visual Studio project files (.vcproj/.vcxproj) for building. To build:

1. Open the appropriate project files in Visual Studio
2. Configure the build settings as needed
3. Build the solution

For automated building, see the build scripts in the `VNC/Builder/` directory.

## Configuration

Configuration files can be found in:
- `BC/bcserver.ini` - Server configuration
- `VNC/Builder/vnc.ini` - VNC configuration

## Dependencies

- Windows SDK
- aPLib compression library (included)

## License

This software is proprietary and confidential.

---

© 2025 NosfirLabs. All rights reserved.
