
# macOS Setup

## Starship install

```bash
curl -sS https://starship.rs/install.sh | sh
```

## Homebrew Install

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

## Rclone Install

```bash
curl https://rclone.org/install.sh | sudo bash
```

## Homebrew apps

```bash
# terminal apps
brew install \
mpv ffmpeg \
oath-toolkit gawk \
wget youtube-dl annie \
pv sf-pwgen pigz lbzip2 jq rsync \
macfuse \
par2 qrencode scrub \
restic

# programming language
brew install \
go nodejs npm

# fonts
brew tap homebrew/cask-fonts
brew install --cask \
font-victor-mono

brew tap buo/cask-upgrade
```

## Node.js Apps

```bash
npm i -g \
nodemon http-server zx
```

## Golang Apps

```bash
#go-sockaddr
go install github.com/hashicorp/go-sockaddr/cmd/sockaddr@latest
```
