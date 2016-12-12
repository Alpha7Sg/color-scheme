#How to install

## Prerequisit

1. Install Homebrew: `/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"`
Node must be installed in your machine. You can use BREW: `brew install node`

## Installation:

1. Install LESS compiler: `npm install -g less`
2. Install Http-server: `npm install http-server -g`
3. Create directory `sudo mkdir /alpha7`
4. Go to directory `cd /alpha7`
5. Clone repository: `git clone https://github.com/Alpha7Sg/color-scheme.git color-scheme`

# How to use

1. Edit colors in color.less
2. Go in terminal
3. type `cd /alpha7/color-scheme`
4. type `lessc main.less > main.css`
5. type `http-server` and check the url given. Usually `http://localhost:8080`
6. Use explorer and type the above url to see the color scheme


As a side note, you may want to open the developer tools and disable cache so you can easily see changes.