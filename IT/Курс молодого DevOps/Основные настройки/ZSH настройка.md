``` bash 
sudo apt install zsh
```

### Oh my zsh
``` bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/robbyrussell/oh-my-zsh/master/tools/install.sh)"
```

##### zsh-autosuggestions
``` bash
git clone https://github.com/zsh-users/zsh-autosuggestions.git $ZSH_CUSTOM/plugins/zsh-autosuggestions
```

##### zsh-syntax-highlighting
``` bash
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git $ZSH_CUSTOM/plugins/zsh-syntax-highlighting
```

##### Файл zshrc
``` 
ZSH_THEME="eastwood"
plugins=(git zsh-autosuggestions zsh-syntax-highlighting)
```

``` bash
chsh -s /usr/bin/zsh
```
