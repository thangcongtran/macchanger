# MAC Address Changer

This Python script allows you to change the MAC address of a network interface on a Linux machine. It leverages the `ifconfig` command to bring the network interface down, change the MAC address, and bring the interface back up.

## Requirements

- Python 3.x
- Linux (Ubuntu, Arch, or other distributions with `ifconfig` command)
- `sudo` privileges to change MAC address

## Features

- Change the MAC address of a specified network interface.
- Check the current MAC address of a network interface.
- Simple and easy-to-use command-line interface.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/thangcongtran/macchanger.git
   cd macchanger
2. . **Usage**

    ```bash
   sudo python3 macchanger.py -i <interface> -m <new_mac_address>
   #Examples
   sudo python3 macchanger.py -i wlan0 -m 00:11:22:33:44:d5


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Disclaimer

Changing your MAC address may disrupt your network connection or cause other issues. Use this script responsibly. The author is not responsible for any potential damage, loss of connectivity, or other consequences that may arise from the use of this tool.
