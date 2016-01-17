# backup-unix
A basic backup and tar script for unix, linux, and mac
NOTES:
Put this file into $HOME/bin
Requires conf file with name $HOME/etc/backup.conf (This file is "sourced")
Make sure that backup.conf has the correct settings
Make sure that the backup destination resides on a mounted filesystem.
Some error checking is done like file/dir existence testing
The tar is silent and no messages are printed until the end. (to show messages, change the tar command to: "tar vfc")

