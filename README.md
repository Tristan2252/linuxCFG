
#LinuxCFG

This program is designed help execute common tasks used after installing a
new Debian OS such as Ubuntu.

- Update
The update function runs Linux update and upgrade commands.
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade

- Pycharm
This function downloads and installs Pycharm IDE. When clicked on the user
is presented with a dialog asking the current version of Pycharm as well as
the desired installation location.

- Webmin
This function installs the Webmin service as well as its required dependencies

- Common App's
Common App's installs common applications that the user will need after installing
a new Linux OS such as:
                       gedit, ubuntu-restricted-extras, chromium-browser, preload,
                       icedtea-7-plugin openjdk-7-jre, openjdk-7-jdk, gnome-terminal,
                       pepperflashplugin-nonfree, tmux, vim, htop, and git
The user is also prompted with the option to install Atom text editor, SSH server,
and playonlinux with wine

- Gnome PPA
Gnome ppa adds the gnome staging repo to linux repos and then runs update and upgrade
with optional gnome-shell install


