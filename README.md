# MinKNOW_Updating
Troubleshooting updating error
Tupdate MinKNOW to a new version:

sudo apt clean
sudo apt update
sudo apt install ont-standalone-minknow-releas

E: Could not open lock file /var/lib/apt/lists/lock - open (13: Permission denied)
Solution: sudo mv /var/lib/apt/lists{,july12}
Re-run the previous commands
