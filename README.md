# OpenJDK installation

![OpenJDK](https://img.shields.io/badge/OpenJDK-18-orange)

Instructions to install [OpenJDK](https://jdk.java.net) on different platforms.

---
## Ubuntu Linux

On [Ubuntu](https://ubuntu.com) just do:

    sudo apt install openjdk-18-jdk

Or if you are in a headless environment:

    sudo apt install openjdk-18-jdk-headless

---
## Windows

On Windows you can use [Eclipse Temurin](https://adoptium.net/temurin/releases/?version=18) at https://adoptium.net/temurin/releases/?version=18

In fact, you could use the above distributions on many platforms. But I prefer a manual direct installation for macOS.

---
## macOS

For macOS I have my own script. Super easy to use, no root needed, and idempotent (you can ignore errors). Run the following on a terminal.

For macOS-AArch64:

    curl -s https://raw.githubusercontent.com/GlitchyByte/openjdk-install-scripts/main/jdk.18/install-openjdk-18-macos-aarch64 | sh

For macOS-x64:

    curl -s https://raw.githubusercontent.com/GlitchyByte/openjdk-install-scripts/main/jdk.18/install-openjdk-18-macos-x64 | sh
