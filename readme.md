#How to install

## Prerequisit

1. Install Homebrew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
Node must be installed in your machine. You can use BREW: `brew install node`

## Installation:

1. Install LESS compiler: "npm install -g less"
2. Create directory `sudo mkdir /alpha7`
3. Go to directory `cd /alpha7`
2. Clone repository: `git clone https://github.com/Alpha7Sg/color-scheme.git color-scheme`

# How to use

1. Edit colors in color.less
2. Go in terminal
3. type "cd /alpha7/color-scheme"
4. type "lessc main.less > main.css"
5  copy the content of "main.css" into the "<style></style>" inside index.html
6. Use explorer and open index.html in a browser