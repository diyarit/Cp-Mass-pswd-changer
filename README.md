# reset_cpanel_users
This script resets ALL cPanel user account passwords to random 16-digit  passwords.  All output is put into a text file called "new-pass.txt" in the directory where this script is being run.

Once complete, it then syncs that new password with MySQL and the FTP databases.
