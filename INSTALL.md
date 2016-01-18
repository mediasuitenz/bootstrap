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
        - If this command gives you an error regarding not being available via software update then you can also download it by launching Xcode -> Xcode menu -> Open Developer Tools... This will take you to an Apple dev tools site.
        - `xcode-select --install`
    - iterm2 (replacement for native terminal app)
        - download binary package from `http://www.iterm2.com`
    - zsh (replacement for bash shell)
        - `brew install zsh`
    - ohmyzsh (zsh configured and enhanced)
        - `curl -L http://install.ohmyz.sh | sh`
    - change your default shell to zsh
        - `chsh -s /bin/zsh`
    - nodejs (Node and NPM)
        - download binary from `http://nodejs.org` or `brew install node`
    - screenhero (Screensharing and pair programming tool)
        - download binary package from `http://screenhero.com/download.html`
    - sequel pro (Mysql management tool)
        - download binary package from `http://www.sequelpro.com/download`
    - pgadmin3 (Postgres management tool)
        - download binary package from `http://www.pgadmin.org/download/macosx.php`
    - heroku toolbelt (Command line tools for working with heroku projects)
        - `brew install heroku-toolbelt` or from binary `https://toolbelt.heroku.com`
    - virtualbox (Virtualmachine provider)
        - download binary package from `https://www.virtualbox.org/wiki/Downloads`
    - vagrant (Virtualmachine controller)
        - download binary package from `https://www.vagrantup.com/downloads.html`
    - hub (github tools)
        - `brew install hub`
    - dash (offline documentation)
        - app store using developers@mediasuite.co.nz itunes store account

## Browsers

- Installs
    - chrome    (download binary package)
    - firefox   (download binary package)

## Communication tools

- Installs
    - slack   (group chat)
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
