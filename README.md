# vRouter-5600-VPN-reset-script

This script will check the ike status of a VPN on vRouter 5600 and reset the VPN if needed. Place in /config/scripts and add entry in crontab with endpoint IP - 

*/5 * * * * /config/scripts/resetVPN.script x.x.x.x

It seems a bug is preventing DPD from working properly and so this script is necessary until bug resolved.
