# My Ansible configuration

## Apps installed with brew cask
- 1password
- adobe-acrobat-reader
- cleanmymac
- dropbox
- firefox
- flux
- google-chrome
- istat-menus
- iterm2
- nextcloud
- skype
- slack
- spectacle
- spotify
- virtualbox
- atom
- visual-studio-code
- vlc
- whatsapp

## Run

1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
2. [Install Ansible](http://docs.ansible.com/intro_installation.html).
3. `ansible-galaxy install -r requirements.yml`
4. `ansible-playbook playbook.yml -i hosts -K`
