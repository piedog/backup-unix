# backup-unix
A basic backup and tar script for unix, linux, and mac
NOTES:
* Put this file into $HOME/bin
* Make sure that backup.conf has the correct settings
* Make sure that the backup destination resides on a mounted filesystem.
* Some error checking is done like file/dir existence testing
* The tar is silent and no messages are printed until the end. (to show messages, change the tar command to: "tar vfc")

The backup script started out as a way to use the backup/restore utility to backup a unix/linux system to a remote freebsd file server.  Later, the script was modified to backup a Mac OS machine to a windows share. I intend to merge the various scripts in the TODO.merge directory into a single script.

xx
