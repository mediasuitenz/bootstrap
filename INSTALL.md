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

## Developer tools

- Installs
    - xcode (Apples horrible piece of junk)
        - app store (after installing, open and accept user license)
    - xcode command line tools
        - `xcode-select --install`
    - iterm2 (replacement for native terminal app)
        - download binary package from `http://www.iterm2.com`
    - zsh (replacement for bash shell)
        - `brew install zsh`
    - ohmyzsh (zsh configured and enhanced)
        - `curl -L http://install.ohmyz.sh | sh`
    - nodejs (Node and NPM)
        - download binary from `http://nodejs.org` or `brew install node`
    - screenhero (Screensharing and pair programming tool)
        - download binary package
    - sequel pro (Mysql management tool)
        - download binary package
    - pgadmin3 (Postgres management tool)
        - download binary package
    - heroku toolbelt (Command line tools for working with heroku projects)
        - `heroku-toolbelt`
    - virtualbox (Virtualmachine provider)
        - download binary package
    - vagrant (Virtualmachine controller)
        - download binary package
    - hub (github tools)
        - `brew install hub`
    - dash (offline documentation)
        - app store using developers@mediasuite.co.nz itunes store account

## Browsers

- Installs
    - chrome    (download binary package)
    - opera     (download binary package)
    - firefox   (download binary package)

## Communication tools

- Installs
    - hipchat   (group chat)
        - download binary package
    - skype     (video chat)
        - download binary package

## Other popular apps

- Installs
    - spotify   (music)
    - mplayerx  (video player that plays just about anything)
    - caffeine  (keeps your screen awake)
    - shiftit   (windows like window snapping)
    - dropbox   (filesharing)

## Nice to haves one day

- Installs
    - TMUX (needs to work with iterm2)

## Stuff boxen used to install
(and I have no idea what does)

- Installs
    - autoconf
    - inifile
    - openssl
    - repository
    - stdlib
    - sudo
    - xquartz
