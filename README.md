# Environment

Open Terminal and follow the steps below to execute.

## Homebrew Install
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

For **Intel CPU**
```sh
echo 'eval "$(/usr/local/bin/brew shellenv)"' >> ~/.zshrc
eval "$(/usr/local/bin/brew shellenv)"
source ~/.zshrc
```

for **M1, M2 and Above**
```sh
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zshrc
eval "$(/opt/homebrew/bin/brew shellenv)"
source ~/.zshrc
```

```sh
brew bundle --file=Brewfile
```
