sudo apt install snapd

//under search for apps under
https://snapcraft.io/store
//or search from terminal
snap find <search_text>

sudo snap install <package>
snap list
snap changes

//which snap package has updates to be
//this command is import because if a snap package is already the newst version
//and I say refresh, it throws an error!
sudo snap refresh --list

//to upgrage a snap package or downgrade
sudo snap refresh <package>
sudo snap revert <package>

sudo snap remove <package>