# Applications

Homebrew
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Terminal Setup
```sh
brew install iterm2 zsh
```

Download .zshrc config file
```sh
curl https://github.com/levensailor/macos-setup/.zshrc -o ~/.zshrc
```

Install oh-my-zsh (optional)
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Applications
```sh
brew install maccy postman audacity wget spotify ssh-copy-id jq git ngrok neofetch jq node nvm npm python3 gimp visual-studio-code
```

Git Configuration
```sh
git config --global user.email "jlevensailor@presidio.com"
```
```sh
git config --global user.name "Jeff Levensailor"
```

Install XCode Developer Tools
```sh
xcode-select --install
```

Generate an RSA key for SSH
```sh
ssh-keygen -t rsa
```

Remove JamF (optional)
```sh
sudo jamf -removeFramework
```

Setup Docker
```sh
brew install nerdctl lima && limactl start
```

