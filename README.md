# Applications

Homebrew
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Applications
```sh
brew install $(<packages.txt)
```

Terminal
```sh
curl https://github.com/levensailor/macos-setup/.zshrc -o ~/.zshrc
```

Install oh-my-zsh (optional)
```sh
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

Git Configuration
```sh
git config --global user.email "jlevensailor@presidio.com" && git config --global user.name "Jeff Levensailor"
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


