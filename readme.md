# Pop-OS specific environment

## Instructions

#### Oh My ZSH / Powerline

* Oh My ZSH
```
wget https://github.com/robbyrussell/oh-my-zsh/raw/master/tools/install.sh -O - | zsh

```

* Edit "theme" line to show `powerline`.

* See [Instructions for Powerline](https://github.com/romkatv/powerlevel10k#manual)
```
git clone --depth=1 https://gitee.com/romkatv/powerlevel10k.git ~/powerlevel10k

echo 'source ~/powerlevel10k/powerlevel10k.zsh-theme' >>~/.zshrc
```


### Follow-on (with this repo)

* Clone repo: `git clone https://github.com/ahplummer/popos-env && cd popos-env`.

* Open your shell's specific config: `vim ~/.zshrc`.

* Add the following lines to the bottom: 
```
export gitname=<your name>
export gitaddress=<your email address>
source ~/<cloned-dir>/aliases
```

* Restart shell.
