# WD 8TB My Cloud EX2 Ultra Network Attached Storage - NAS - WDBVBZ0080JCH-NESN       



https://www.amazon.com/Cloud-Ultra-Network-Attached-Storage/dp/B01AWH05GE/ref=sr_1_1?crid=37K22QMNQ2V8M&keywords=mycloud%2Bwd&qid=1644443980&sprefix=my%2Bcloud%2Bw%2Caps%2C283&sr=8-1&th=1



$350, can price match with BestBuy

## Setup with openmediavault

https://www.howtoforge.com/tutorial/install-open-media-vault-nas/

## Connecting users

https://forum.openmediavault.org/index.php?thread/27271-how-to-connect-to-omv-smb-shares-with-windows-10/



## Remote Access

https://ameridroid.com/blogs/ameriblogs/setting-up-openmediavault-remote-access-with-openvpn





<hr>

## How to setup openmediavault

1. Setup the new debian server (openmediavault)
   1. Plugin installation media
   2. Default setup
   3. Make sure to connect with correct ethernet/wireless connection
      1. What is the hostname? jekyll
      2. What is the IP address? at work: 
      3. What is the domain name? work: glover.intra, lan or other
   4. Set root domain password
   5. Install OS to the correct external harddrives
2. Create the RAID array
   1. Disks > confirm disks are set
   2. Storage > Pools > Add
   3. Available disks -> Data VDevs, don't forget to put a name [storage]; set as RAID-z
3. Create the share directory
   1. Sharing > SMB (Windows) > Add
   2. Create the set of share folders
      1. /mnt/storage/**home**; use as home share
      2. /mnt/storage/**admin**; high level security
      3. /mnt/storage/**public**; public docs to share for everyone
   3. set appropriate acl for each



<hr>

<hr> https://www.truenas.com/community/threads/how-to-set-up-truenas-from-beginning-to-end-including-secure-remote-access-to-files-and-web-gui.89229/



