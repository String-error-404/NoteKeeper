# NoteKeeper



btrfs snapshots 



make btfs property to writeable 

#### sudo btrfs property set -ts /.snapshots/$/snapshot/ ro false


from arch iso 


### mount /dev/sdb2 /mnt

##### to looking throught the snapshots


vim /mnt/@snapshots/$/info.xml


rm -rf /mnt/@root



btrfs subvol snapshot /mnt/@snapshots/$/snapshots /mnt/@root
