
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
coreutils htop pv pigz \
rhash par2 \
mpv ffmpeg \
oath-toolkit gawk \
wget socat rsync youtube-dl annie \
sf-pwgen lbzip2 jq \
qrencode scrub \
macfuse \
restic

# apps
brew install \
google-chrome visual-studio-code \
max rectangle vlc handbrake \
resilio-sync

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
