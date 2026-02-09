# nix-openclaw

> Ref: https://stacker.news/items/1423749

## Installation

```bash
mkdir -p ~/Documents
cd ~/Documents
git clone git@github.com:ysl2/nix-openclaw.git
cd nix-openclaw
devbox shell
openclaw onboard
systemctl --user link .home/.config/systemd/user/openclaw-gateway.service
systemctl --user daemon-reload
systemctl --user start openclaw-gateway
openclaw gateway install
```
