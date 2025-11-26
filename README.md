# Telecom Project

This project aims to develop a comprehensive telecom solution, including cellular network components and services.

## Directories

- `cellular_core/`: Contains the implementation of a free5gc core network.
- `ran_emu/`: Provides an emulation of a 5G AMF, gNB, and UE written in Python.

## Installation

To set up the project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Samland-Gov/telecom.git
    ```
2. Navigate to the project directory:
    ```bash
    cd telecom
    ```
3. Start the all services:
    ```bash
    docker compose up -d
    ```

## License

Licensed under the Apache License, Version 2.0. See the [LICENSE.txt](LICENSE.txt) file for details.