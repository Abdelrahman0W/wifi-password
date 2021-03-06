# Wi-Fi Password

![Badge](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Badge](https://img.shields.io/github/repo-size/Abdelrahman0W/wifi-password?style=for-the-badge)
![Badge](https://img.shields.io/github/last-commit/Abdelrahman0W/wifi-password?style=for-the-badge)
![Badge](https://img.shields.io/github/contributors/Abdelrahman0W/wifi-password?style=for-the-badge)

- [Wi-Fi Password](#wi-fi-password)
    - [Description](#description)
    - [Installation](#installation)
        - [Linux/Unix](#linux/unix)
        - [Windows](#windows)
    - [Usage](#usage)
        - [Linux/Unix](#linux/unix)
        - [Windows](#windows)
    - [Used Libraries](#used-libraries)
    - [Credits](#credits)

## Description

A python CLI package to generate a QR Code for the current Wi-Fi network or a new network.

## Installation

### Linux/Unix

1. Clone this repo.

    ```bash
    git clone https://github.com/Abdelrahman0W/wifi-password.git
    ```
1. Change directory to the repo directory.

    ```bash
    cd wifi-password
    ```
1. Install the package from current directory using `pip`

    ```bash
    python3 -m pip install wifi-password ./
    ```

### Windows

> Kindly note that there is an issue installing the package on windows that I am working on to fix. You can still use the package as mentioned in [usage](#usage) section.

## Usage

### Linux/Unix

1. Run the python module.

    ```
    python3 -m wifi-password
    ```

### Windows

> As mentioned before there is an issue installing the package on windows so you have to run it from its local directory till the issue got resolved.

1. Clone this repo.

    ```bash
    git clone https://github.com/Abdelrahman0W/wifi-password.git
    ```
1. Change directory to the repo directory.

    ```bash
    cd wifi-password
    ```
1. Run the python module.

    ```
    python3 -m wifi-password
    ```

## Used Libraries

1. [Inquirer](https://github.com/magmax/python-inquirer).
1. [qrcode](https://github.com/lincolnloop/python-qrcode).

## Credits

This repo mainly inspired by my friend, Ibrahim Abou Elenein's repo: [aboueleyes/wifi-password](https://github.com/aboueleyes/wifi-password).
