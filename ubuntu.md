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

## Visual Studio Code

### Install

```sh
sudo apt update
sudo apt install software-properties-common apt-transport-https wget
wget -q https://packages.microsoft.com/keys/microsoft.asc -O- | sudo apt-key add -
sudo add-apt-repository "deb [arch=amd64] https://packages.microsoft.com/repos/vscode stable main"
sudo apt install code
```

### Font

[Download font from here](https://drama-sans.github.io/drama-sans/DramaSans.ttf)

### Extensions

-   Angular Language Service
-   Better Comments
-   Bracket Pair Colorizer
-   colorize
-   ES7 React/Redux/GraphQL/React-Native snippets
-   Simple React Snippets
-   ESLint
-   Prettier - Code formatter
-   HTML Biscuits
-   indent-rainbow
-   Live Share
-   Markdown Preview Enhanced
-   PostCSS Language Support
-   Power Mode
-   Pylance
-   Tailwind CSS IntelliSense
-   Community Material Theme (Ocean High Contrast)
-   background

### Settings

It can be found in `./vscode/settings.json`.

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

-   extend-height -> false
-   dock-position -> BOTTOM
-   transparency-mode -> FIXED
-   unity-backlit-items -> true

