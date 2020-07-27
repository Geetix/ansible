# My MacOS clean install

`brew cask install \
1password \
adobe-acrobat-reader \
firefox \
firefox-developer-edition \
google-chrome \
istat-menus \
iterm2 \
nextcloud \
slack \
spectacle \
spotify \
visual-studio-code \
goland \
whatsapp \
discord \
joplin \
zoomus`

## With Ansible

For the moment, only my apps are installed.

### Apps installed with `brew cask`
- 1password
- adobe-acrobat-reader
- firefox
- firefox-developer-edition
- google-chrome
- istat-menus
- iterm2
- nextcloud
- slack
- spectacle
- spotify
- visual-studio-code
- goland
- whatsapp
- discord
- joplin
- zoomus

### Run

1. Ensure Apple's command line tools are installed (`xcode-select --install` to launch the installer).
2. [Install Ansible](http://docs.ansible.com/intro_installation.html).
3. `ansible-galaxy install -r requirements.yml`
4. `ansible-playbook playbook.yml -i hosts -K`
