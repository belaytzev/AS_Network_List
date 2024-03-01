# AS Network List

This repository contains two Python scripts that allow you to retrieve network lists based on either an Autonomous System (AS) name or a Network name.

## Features

- `network_list_from_as.py`: Retrieves a list of networks associated with a given AS name.
- `network_list_from_netname.py`: Retrieves a list of networks associated with a given Network name.

These scripts have been tested on MacOS and Linux.

## Prerequisites

- Python 3: Download it from the [official website](https://www.python.org/downloads/).

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/C24Be/AS_Network_List.git
    ```

2. Navigate to the repository folder:

    ```bash
    cd AS_Network_List
    ```

3. Install the required Python packages:

    ```bash
    ./requirements.sh
    ```

## Usage

### `network_list_from_as.py`

1. Run the script with the AS number as an argument:

    ```bash
    ./network_list_from_as.py AS61280
    ```

2. To suppress all output except the prefixes, use the `--quiet` or `-q` switch:

    ```bash
    ./network_list_from_as.py AS61280 -q
    ```

3. To display a help message, use the `-h` or `--help` switch:

    ```bash
    ./network_list_from_as.py --help
    ```

### `network_list_from_netname.py`

1. Run the script with a file containing a list of network names as an argument:

    ```bash
    ./network_list_from_netname.py files/blacklist4.txt
    ```

2. Run the script with a URL to a file in a GitHub repository as an argument:

    ```bash
    ./network_list_from_netname.py https://github.com/AntiZapret/antizapret/blob/master/blacklist4.txt
    ```

    Or better use the raw file link:

    ```bash
    ./network_list_from_netname.py https://raw.githubusercontent.com/AntiZapret/antizapret/master/blacklist4.txt
    ```

3. To display a help message, use the `-h` or `--help` switch:

    ```bash
    ./network_list_from_netname.py --help
    ```

## Screenshots

<img width="480" alt="image" src="https://github.com/C24Be/AS_Network_List/assets/153936414/574b072c-9104-4e02-b2c0-3609433bdfc4">
<img width="1280" alt="image" src="https://github.com/C24Be/AS_Network_List/assets/153936414/354cd189-63d6-4685-953d-2d07cb1f8ace">
