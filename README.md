# Applications and tools to Install

## Dependencies

- Installs
    - java (bundled in earlier versions of Mac OSX)
        - (Mavericks) `http://support.apple.com/kb/DL1572?viewlocale=en_US`
    - ruby
        - `curl -L https://get.rvm.io | bash -s stable --rails --autolibs=enabled # Or, --ruby=1.9.3`

## Package manager (homebrew)

Quite a few things can be installed via homebrew using `brew install`. You can use
`brew search` to find packages and `brew list` to see installed packages. If you have
any problems try running `brew doctor` as a first step

- Installs
    - homebrew `ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"`
    - `brew install cask` to be able to install binaries like Firefox

## Developer tools

- Installs
    - xcode (Apples horrible piece of junk)
        - app store (after installing, open and accept user license)
    - xcode command line tools
        - If this command gives you an error regarding not being available via software update then you can also download it by launching Xcode -> Xcode menu -> Open Developer Tools... This will take you to an Apple dev tools site.
        - `xcode-select --install`
    - iterm2 (replacement for native terminal app)
        - download binary package from http://www.iterm2.com
    - zsh (replacement for bash shell)
        - `brew install zsh`
        - review and copy the config files from this repo config-files/.zshrc
    - ohmyzsh (zsh configured and enhanced)
        - `curl -L http://install.ohmyz.sh | sh`
    - change your default shell to zsh
        - `chsh -s /bin/zsh`
    - nodejs (Node and NPM)
        - download binary from http://nodejs.org or `brew install node`
        - Install n (node version manager) `npm install -g n`
        - `which node` and `which npm` should return valid paths, if not try adding `export PATH=/path/to/node/bin:$PATH` to your .zshrc
    - Install 'n' and switch to node LTS 4.2
        - install npm n package with `npm install -g n`
        - install node v4.4, the current LTS `n 4.4`
    - screenhero (Screensharing and pair programming tool)
        - download binary package from http://screenhero.com/download.html
    - sequel pro (Mysql management tool)
        - download binary package from http://www.sequelpro.com/download
    - Postgres.app
        - http://postgresapp.com/
        - add postgres tools to path by adding `export PATH=$PATH:/Applications/Postgres.app/Contents/Versions/9.4/bin` to your .zshrc
    - Postico
        - `brew cask install postico`  
    - heroku toolbelt (Command line tools for working with heroku projects)
        - `brew install heroku-toolbelt` or from binary https://toolbelt.heroku.com
    - virtualbox (Virtualmachine provider)
        - download binary package from https://www.virtualbox.org/wiki/Downloads
    - Docker for Mac
        - https://docs.docker.com/docker-for-mac/
    - vagrant (Virtualmachine controller)
        - download binary package from https://www.vagrantup.com/downloads.html
    - hub (github tools)
        - `brew install hub`
    - dash (offline documentation)
        - app store using developers@mediasuite.co.nz itunes store account
    - AWS Elastic Beanstalk Command Line Interface (provides eb command)
        - `brew install aws-elasticbeanstalk`

## Time-tracking

- Toggl (desktop app for time tracking)
    - `brew cask install toggldesktop`
- Jiggl-ui
    - https://github.com/mediasuitenz/jiggl-ui

## Browsers

- Installs
    - chrome    (download binary package)
        - `brew cask install chrome`
    - firefox   (download binary package)
        - `brew cask install firefox` 

## Git Config
- Create a key and add it to github: https://help.github.com/articles/generating-ssh-keys
- `git config --global user.name "John Doe"`
- `git config --global user.email johndoe@example.com`
- `git config --global color.ui true`
- `git config --global color.diff.whitespace "red reverse"`

## Communication tools

- Installs
    - slack   (group chat)
        - `brew cask install slack`
    - skype     (video chat)
        - `brew cask install skype`
    - zoom
        - https://zoom.us/download

## Other popular apps

- Installs
    - mpv  video player that plays just about anything
    - caffeine  keeps your screen awake
    - spectacle   window arrangement shortcuts
