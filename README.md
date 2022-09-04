```bash
sudo add-apt-repository ppa:wireshark-dev/stable
sudo apt update
sudo apt install wireshark

sudo dpkg-reconfigure wireshark-common

sudo usermod -aG wireshark $(whoami)
```
