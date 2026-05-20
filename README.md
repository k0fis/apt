# k0fis APT Repository

APT repository for k0fis packages, served via GitHub Pages.

## Setup

```bash
curl -fsSL https://k0fis.github.io/apt/gpg.key | sudo gpg --dearmor -o /usr/share/keyrings/k0fis.gpg
echo "deb [signed-by=/usr/share/keyrings/k0fis.gpg] https://k0fis.github.io/apt stable main" | sudo tee /etc/apt/sources.list.d/k0fis.list
sudo apt update
```

## Available packages

- **kfs-tg** — Minimalist TUI Telegram client

## Install

```bash
sudo apt install kfs-tg
```

## Update

```bash
sudo apt update && sudo apt upgrade kfs-tg
```
