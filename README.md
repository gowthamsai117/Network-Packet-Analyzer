# Packet Sniffer Tool

## Introduction

The Packet Sniffer Tool is designed for educational purposes to capture and analyze network packets. It displays relevant information such as source and destination IP addresses, protocols, and payload data. This tool is intended for ethical use only.

## Features

- **Packet Capture**: Captures network packets in real-time.
- **Packet Analysis**: Analyzes captured packets and extracts information such as source and destination IP addresses, protocols, and payload data.
- **User-Friendly Interface**: Provides a simple command-line interface for users to view captured packet data.

## Installation

### Prerequisites

- Python 3.x
- `scapy` library

### Installing the Tool

1. Clone the repository:
    ```bash
    git clone https://github.com/gowthamsai117/packet-sniffer-tool.git
    cd packet-sniffer-tool
    ```

2. Create a virtual environment (optional but recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

### Installing `scapy`

If `scapy` is not included in the `requirements.txt` file, install it manually:
```bash
pip install scapy
```
