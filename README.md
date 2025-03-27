<p align="center">
<a href="https://github.com/iniridwanul/manpac"><img src="https://raw.githubusercontent.com/iniridwanul/manpac/refs/heads/master/assets/manpac.png" height="128" width="128" alt="manpac"/></a>
</p>

<p align="center">
<b>manpac</b><br/>
manpac updates mirrors, upgrades Arch, and reports status to Telegram.
</p>

## About manpac
**manpac** is a smart automation script for Arch Linux that updates the mirrorlist, upgrades system packages, and sends system status reports, including date and time, to a specified Telegram chat.

## Features
- Fetches and updates the latest Arch Linux mirrorlist.
- Synchronizes and upgrades system packages using pacman.
- Sends a system report to Telegram, including:
   * Distribution name
   * Kernel version
   * Hostname
   * Current user
   * Date and time
   * Upgrade status

## Requirements
- Arch Linux-based distribution.
- curl (for fetching data and sending messages).
- pacman (for package management).

## Installation
* Clone the repository:
   * ```shell
      git clone https://github.com/iniridwanul/manpac.git
      ```
* Navigate to the manpac directory:
   * ```shell
      cd manpac
      ```
* Make the script executable:
   * ```shell
      chmod +x manpac
      ```
* Edit the script to add your Telegram bot token and chat ID:
   * ```shell
      nano manpac
      ```
Replace `YOUR_BOT_TOKEN_HERE` and `YOUR_CHAT_ID_HERE` with your actual Telegram credentials.

## Usage
Run the script with:
```shell
./manpac
```

or

```shell
bash manpac
```

## Contributing
Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.