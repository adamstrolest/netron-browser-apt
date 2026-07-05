# Netron Browser APT Repository

This repo hosts .deb packages for [Netron Browser](https://adamstrolest.github.io/netron-browser-site).

## Usage

```bash
# Add the repository
echo "deb [trusted=yes] https://adamstrolest.github.io/netron-browser-apt stable main" | sudo tee /etc/apt/sources.list.d/netron-browser.list
sudo apt update
sudo apt install netron-browser
```

## Manual download

Download the latest `.deb` from [Releases](https://github.com/adamstrolest/netron-browser-apt/releases) or directly from `pool/main/`.
