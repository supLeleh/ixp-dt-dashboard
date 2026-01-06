# IXP Digital Twin GUI

Web-based graphical interface for managing and monitoring IXP network emulation labs powered by Kathará.

## Overview

This application provides an intuitive interface to control Internet Exchange Point (IXP) network topologies. It consists of a FastAPI backend that interfaces with Kathará for network emulation and a React frontend for visualization and control.

### Key Features

- Start, stop, and reload network labs
- Real-time device monitoring
- Configuration file management
- Command execution on devices
- RIB diff analysis

## Project Structure

ixp-digital-twin-gui/
├── backend/ # FastAPI REST API server
└── frontend/ # React web application

## Getting Started

For detailed installation and usage instructions, please refer to:

- **Backend Setup**: [`backend/README.md`](backend/README.md)
- **Frontend Setup**: [`frontend/README.md`](frontend/README.md)