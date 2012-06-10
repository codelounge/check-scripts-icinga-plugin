check-scripts-icinga-plugin
===========================

Nagios/Icinga Plugin to check script version of WordPress, IP.Board, vBulletin

Usage
-----
>	check_scrips -h <HOSTADRESS> -s <SCRIPTNAME> (-v <VERISON_NUMBER>) (-d)

The following scripts are supported:
+ wordpress = WordPress
+ vbulletin = vBulletin
+ ipb = IP.Board

Hint
----
The Plugin only works if the script version is displayed on the website (vBulletin, IP.Board) or is within the META-Tags (WordPress).