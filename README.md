# Transmission Remote

Script for calling transmission-remote via FreeNAS CLI, without having to enter the transmission jail.

# To install

1. Download the script to /sbin
2. Run `chmod +x /sbin/transmissionRemote`

`sudo git clone https://github.com/justinmancini/transmissionRemote /sbin; sudo chmod +x /sbin/transmissionRemote; sudo rm /sbin/README.md`

# To use

Run `transmissionRemote <option> <argument>`

Available options are:

    start (Requires torrent ID as argument)
    stop (Requires torrent ID as argument)
    remove (Requires torrent ID as argument)
    startAll
    stopAll
    removeAll
    list
