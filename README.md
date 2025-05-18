## More About Me – [Take a Look!](http://www.mjakaria.me) 

### Welcome to Terminal Configuration on MacOS/Linux

#### Homebrew Install (for MacOS)
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
# add path
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/[USERNAME]/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```

#### iTerm2 Install (Optional for MacOS & Not Necessary for Linux)
```bash
brew install --cask iterm2
```

#### Install Git
```bash
brew install git # for MacOS
apt install git # for ubuntu
sudo dnf install git # for redhat
sudo dnf install epel-release
```
#### Install zsh only for Linux, Already installed on MacOS
```bash
apt install zsh
dnf install zsh
```

#### Install Oh My Zsh
```bash
sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### Install PowerLevel10K Theme for Oh My Zsh
```bash
apt install fonts-font-awesome # for ubuntu
sudo dnf install fontawesome-fonts # for redhat
dnf search awesome | grep font # check
git clone https://github.com/romkatv/powerlevel10k.git $ZSH_CUSTOM/themes/powerlevel10k
# zsh_theme add into '~/.zshrc'
ZSH_THEME="powerlevel10k/powerlevel10k"
# load these new plugins
source ~/.zshrc
```

#### Font Install
```bash
# put this line on 'setting.json' in vscode.
"terminal.integrated.fontFamily": "monospace, MesloLGS NF, fontawesome"
# You may setup font as default (MesloLGS NF) in you default terminal, then it will work.
```

#### Configuration
```bash
p10k configure
# Here you must answer some questions, give these answer as you want.
```

#### Install ZSH Plugins
```bash
# for auto suggestions
git clone https://github.com/zsh-users/zsh-autosuggestions ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-autosuggestions
# for syntax highlighting
git clone https://github.com/zsh-users/zsh-syntax-highlighting.git ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/zsh-syntax-highlighting
# plugin add into '~/.zshrc'
plugins=(git zsh-autosuggestions zsh-syntax-highlighting web-search)
# load these new plugins
source ~/.zshrc
```

#### Done

## With Regards, `Jakir`

[![LinkedIn][linkedin-shield-jakir]][linkedin-url-jakir]
[![Facebook-Page][facebook-shield-jakir]][facebook-url-jakir]
[![Youtube][youtube-shield-jakir]][youtube-url-jakir]

### Wishing you a wonderful day! Keep in touch.

<!-- Personal profile -->

[linkedin-shield-jakir]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-jakir]: https://www.linkedin.com/in/jakir-ruet/
[facebook-shield-jakir]: https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white
[facebook-url-jakir]: https://www.facebook.com/jakir.ruet/
[youtube-shield-jakir]: https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white
[youtube-url-jakir]: https://www.youtube.com/@mjakaria-ruet/featured
