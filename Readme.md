### rknn system install
- board : aio3588q
- first flashing and put firmware on the device

- in ubuntu (bash)
    ```bash
    sudo apt update && sudo apt upgrade -y
    sudo apt install -y build-essential curl wget git vim nano unzip zip \
    htop net-tools openssh-server software-properties-common

    sudo apt install -y snapd
    sudo apt install chromium-browser

    sudo apt install make
    sudo apt autoremove -y && sudo apt autoclean
    ```

- 콘다 설치
    ```bash
    bash Anaconda3-2024.10-1-Linux-aarch64.sh 
    ```

- vscode 설치
    ```bash
    sudo dpkg -i code_1.96.2-1734606918_arm64.deb 
    ```