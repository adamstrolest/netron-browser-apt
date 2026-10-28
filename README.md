# Netron Browser APT Repository

This repo hosts .deb packages for [Netron Browser](https://adamstrolest.github.io/netron-browser-site).

## Usage

```bash
# Add the signing key
sudo curl -fsSL https://adamstrolest.github.io/netron-browser-apt/netron-browser.gpg \
  -o /usr/share/keyrings/netron-browser.gpg

# Add the repository
echo "deb [signed-by=/usr/share/keyrings/netron-browser.gpg] https://adamstrolest.github.io/netron-browser-apt stable main" \
  | sudo tee /etc/apt/sources.list.d/netron-browser.list

sudo apt update
sudo apt install netron-browser
```

Signing key fingerprint: `B145 F33D 3415 1115 B3FF 0BE9 0607 15FE BE87 93DA`

## Manual download

Download the latest `.deb` from [Releases](https://github.com/adamstrolest/netron-browser-apt/releases) or directly from `pool/main/`.
