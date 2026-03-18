# Billions-agent

# Update soundness
Postingan sebelumnya ada di https://t.me/uangdrop/40872

### Install CLI

```
sudo apt update && sudo apt upgrade -y
sudo apt install openssl libssl-dev pkg-config
```

```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
source ~/.bashrc
```

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
source $HOME/.cargo/env
```

```
soundnessup install
soundnessup update
```

### Import Account Lama Menggunakan Phrase

```
soundness-cli import-key --name my-key --mnemonic "Your Pharse"
```

### Melihat Account Lama yang telah di buat
```
soundness-cli list-keys
```
