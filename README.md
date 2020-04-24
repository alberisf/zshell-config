# My Zshell config

`sudo apt install -y zsh`

`sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"`

`sh -c "$(curl -fsSL https://raw.githubusercontent.com/zdharma/zinit/master/doc/install.sh)"`

`vim ~/.zshrc`

Append to end of file

`zinit light zdharma/fast-syntax-highlighting`

`zinit light zsh-users/zsh-autosuggestions`

`zinit light zsh-users/zsh-completions`

`source ~/.zshrc`
