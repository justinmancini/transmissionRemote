# transmissionRemote

Script for controlling transmission via FreeNAS CLI, without having to enter the transmission jail.

# To install

1. Put the script in /sbin
2. Run `chmod +x /sbin/transmissionRemote`

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
