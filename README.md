# My Ansible configuration

## Apps installed with brew cask
- firefox
- google-chrome
- visual-studio-code
- dropbox
- nextcloud
- slack
- spotify
- istat-menus
- iterm2
- 1password
- spectacle
- whatsapp

## Run 

1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
2. [Install Ansible](http://docs.ansible.com/intro_installation.html).
3. `ansible-galaxy install -r requirements.yml`
4. `ansible-playbook playbook.yml -i hosts -K`
