# Termux-Essential 

## Overview
**Termux-Essential** is a tool designed to simplify the installation of essential packages on Termux, a powerful terminal emulator for Android. With this script, you can quickly set up your Termux environment with vital tools and libraries for software development, system monitoring, and more. The tool is licensed under the **GNU GPL v3.0**, ensuring that it remains free and open-source for all users.

## Features
- **Comprehensive Package Installation**: Includes a wide variety of essential development tools, programming languages, libraries, and utilities.
- **Easy-to-Use**: Just one command to set up all your essential packages.
- **Automated Setup**: No need for manual installation—run the script and relax as your environment is configured.

## Packages Installed
Here are some of the key tools and libraries installed by the script:
- **Programming Languages**: Python, Ruby, Perl, Node.js, PHP, Lua
- **Development Tools**: Git, Clang, Make, CMake, GCC (via binutils), GDB
- **System Utilities**: Curl, Wget, Vim, OpenSSH, Htop, Screen, Neofetch, Tmux
- **Libraries**: libcrypt-dev, libssl-dev, libffi-dev, libsqlite-dev, libjpeg-turbo, libxml2, libxslt
- **Miscellaneous Utilities**: FFmpeg, ncdu, jq, procps, sysstat, iputils, dnsutils, nmap, tshark, socat

For a full list of packages, please refer to the script.

## Installation
To install and use Termux-Essential, run the following commands in your Termux terminal:
```bash
wget https://github.com/linuxfanboy4/termux-essential/raw/main/termux-essential.deb
termux-essential.deb
```

## How It Works
1. **Update and Upgrade**: The script ensures that your package repository is up to date.
2. **Install Essential Packages**: Using the `pkg` command, the script installs all the necessary tools and libraries listed above.
3. **Automated Setup**: The script is designed to handle dependencies and conflicts automatically.

## Usage
After running the installation script, all the packages will be ready to use in your Termux environment. You can start using your tools immediately for software development, testing, or system administration tasks.

## License
This project is licensed under the **GNU General Public License v3.0**. For more details, refer to the [LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html) file.

## Contribution
Contributions are welcome! If you have suggestions or improvements, feel free to fork the repository and submit a pull request.
