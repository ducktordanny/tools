# Ubuntu Setup

> My Ubuntu setup for web developement

## Installations

### Google Chrome

```sh
sudo apt -y install wget
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo apt -y install ./google-chrome-stable_current_amd64.deb
```

### Git

```sh
sudo apt-get update
sudo apt-get install git
```

### Node, npm and yarn

Update node

```sh
sudo npm cache clean -f
sudo npm install -g n
sudo n stable
```

Install yarn

```sh
npm install --global yarn
```

### Insomnia

For testing APIs install insomnia. ([From
here](https://updates.insomnia.rest/downloads/ubuntu/latest?&app=com.insomnia.app&source=website))

### Ulauncher

[Download from here](https://ulauncher.io/#Download)

### Powerlevel10k

Install zsh

```sh
sudo apt -y install zsh
```

[Installation Guide](https://github.com/romkatv/powerlevel10k)

### Cheat and Cheatsheets

[Installation guide](https://kifarunix.com/install-cheat-command-on-ubuntu-20-04/)
Github repos: [Cheat](https://github.com/cheat/cheat) and [Cheatsheets](https://github.com/cheat/cheatsheets)

## Visual Studio Code

### Install

```sh
sudo apt update
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt install code
```

## Other

### Tweaks

Install it from the Ubuntu Software

Setting titlebar buttons to the left in Window Titlebars > Titlebar Buttons >
Placement -> left

### dconf Editor

Use it carefully!

```sh
sudo apt -y install dconf-editor
```

Customizing the doc: org > gnome > shell > extensions > dash-to-dock

- extend-height -> false
- dock-position -> BOTTOM
- transparency-mode -> FIXED
- unity-backlit-items -> true

## General

> Some other useful settings and tools that I'm using, but not really related to any specific OS: [here](./general.md).
